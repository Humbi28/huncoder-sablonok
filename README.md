# HunCoder Sablonok

A HunCoder Sablonok egy Visual Studio Code-ba telepíthető automatikus kitöltő  HTML fájlokhoz. Kezdő webfejleszők munkáját szeretnénk meggyorsítani, behívható magyar parancsokkal, amik automatikusan kitöltik a HunCoder keretrendszerrel készített alap sablonokat. 

## Használat

Egy felkiáltójel beírásával a Visual Studio Code ki fogja listázni az összes parancsot, amit használhatsz. A parancsok nevei megegyeznek a sablonok neveivel, így pontosan tudhatod, hogy melyik sablont szeretnéd beilleszteni.

## Sablonok listája

### Üres sablon
**!ures-sablon** - Üres sablon  

### Elválasztó
**!elvalaszto-1** - Elválasztó 1  

### Fejlécek
**!fejlec-1** - Fejléc 1  
**!fejlec-2** - Fejléc 2  

### Galériák
**!galeria-1** - Galéria 1  
**!galeria-2** - Galéria 2  

### Kártyák
**!kartya-1** - Kártya 1  
**!kartya-2** - Kártya 2  
**!kartya-3** - Kártya 3  

### Láblécek
**!lablec-1** - Lábléc 1  
**!lablec-2** - Lábléc 2  
**!lablec-3** - Lábléc 3  

## Példa

Ahhoz, hogy ne kelljen nulláról megcsinálni az oldalra egy navigációs menüt, elég csak kiválasztani a megfelelő sablont, és beírni a nevét egy felkiáltójel után:

```html
!nav-bal-1
```

Az enter lenyomásával pedig a következőképpen töltődik ki a fájlod:

```html
<nav class="navigacios-sav hatter-paradicsom betutipus-sans-serif" id="menu">
		
	<ul class="lista-navigacio">
			
		<!-- ITT ÁLLÍTHATOD BE A GOMB SZÖVEGÉT ÉS A LINKET -->
		<li>
			<a href="#" class="menupont-balra szoveg-feher betumeret-20px belso-kitoltes-10px felkover aktiv-sotet">Főoldal</a>
		</li>
			
		<!-- ITT ÁLLÍTHATOD BE A GOMB SZÖVEGÉT ÉS A LINKET -->
		<li>
			<a href="#" class="menupont-balra szoveg-feher betumeret-20px belso-kitoltes-10px felkover">Galéria</a>
		</li>
			
		<!-- ITT ÁLLÍTHATOD BE A GOMB SZÖVEGÉT ÉS A LINKET -->
		<li>
			<a href="#" class="menupont-balra szoveg-feher betumeret-20px belso-kitoltes-10px felkover">Kapcsolat</a>
		</li>
			
		<li>
			<a href="#" class="menupont-ikon szoveg-feher betumeret-20px belso-kitoltes-10px felkover" onclick="alkalmazkodoMenuMegnyitas()">
				<i class="fa-solid fa-bars"></i>
			</a>
		</li>
				
	</ul>
			
</nav>
```

**VAGY**

```html
!lablec-1
```

Példa a Lábléc 1 elhelyezése:  

```html
<footer class="lablec belso-kitoltes-10px hatter-paradicsom">
			
	<!-- ITT ÁLLÍTHATOD ÁT A SZÖVEGET -->
	<p class="szoveg-kozepre betutipus-sans-serif szoveg-feher felkover">Szerkesztő neve © 2023</p>
			
</footer>
```

Minden behívható sablon reszponzív.

## Új verzió

### 0.0.10

Láblécek

## HTML kitöltő

Használd HTML kitöltőnket a gyorsabb munkáért. [HTML kitöltő](https://marketplace.visualstudio.com/items?itemName=HunCoder.huncoder-webdev)

## CSS kitöltő

Használd CSS kitöltőnket a gyorsabb munkáért. [HTML kitöltő](https://marketplace.visualstudio.com/items?itemName=HunCoder.huncoder-webdev-css)

## Weboldalunk

Tudnivalókért és további munkáinkért látogass el a weboldalunkra: [HunCoder.hu](http://huncoder.hu)