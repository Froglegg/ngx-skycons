<<<<<<< HEAD
# Ngx Skycons

This is a Skycons library for Angular 7.

Skycons is a weather icon pack made for DarkSky (Forecast). You can find the original pack [here](https://darkskyapp.github.io/skycons/).

You can find the web page and demo of this project here: [https://flexocarpius.github.io/ngx-skycons/](https://flexocarpius.github.io/ngx-skycons/).

# Installation

First install the package.

`npm i --save ngx-skycons`

Then import it into your app.module.ts.

```typescript
import { SkyconsModule } from 'ngx-skycons';
```

And in your imports section

```typescript
  @NgModule({
  declarations: [
    AppComponent,
    ...
  ],
  imports: [
    ...,
    SkyconsModule
  ],
```

Finally, use it on your HTML code

```html
<sc-skycons [weather]="'clear day'" [color]="'white'"></sc-skycons>
```

# Usage

Actually ngx-skycons support this weathers (inside SkyconsTypes):

| Option    | Values                                                                                               | Description                                   |
|-----------|------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| weather   | 'clear day', 'clear night, 'cloudy day', 'cloudy night', 'rain', 'cloudy', 'sleet', 'snow', 'wind'   | The weather to be animated.                   |
| color     | Any CSS color (including hexadecimal format)                                                         | The color that will be used to draw the icon. |
=======
# Ngx Skycons

This is a Skycons library for Angular 7.

Skycons is a weather icon pack made for DarkSky (Forecast). You can find the original pack [here](https://darkskyapp.github.io/skycons/).

Project page and mini demo can be found here: [https://flexocarpius.github.io/ngx-skycons/](https://flexocarpius.github.io/ngx-skycons/).

# Installation

First install the package.

`npm i --save ngx-skycons`

Then import it into your app.module.ts.

```typescript
import { SkyconsModule } from 'ngx-skycons';
```

And in your imports section

```typescript
  @NgModule({
  declarations: [
    AppComponent,
    ...
  ],
  imports: [
    ...,
    SkyconsModule
  ],
```

Finally, use it on your HTML code

```html
<sc-skycons [weather]="'CLEAR_DAY'" [color]="'white'"></sc-skycons>
```

# Usage

Actually ngx-skycons support this weathers (inside SkyconsTypes):

| Option    | Values                                                                                               | Description                                   |
|-----------|------------------------------------------------------------------------------------------------------|-----------------------------------------------|
| weather   | CLEAR_DAY, CLEAR_NIGHT, PARTLY_CLOUDY_DAY, PARTLY_CLOUDY_NIGHT, CLOUDY, RAIN, SLEET, SNOW, WIND, FOG | The weather to be animated.                   |
| color     | CSS color                                                                                            | The color that will be used to draw the icon. |
>>>>>>> 7184ee3c6cf72d25391c8cdc28873b1fe1699ce5
