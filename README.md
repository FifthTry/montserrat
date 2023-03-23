# Montserrat : fastn Font Package

This repository contains a [fpm font package](https://fpm.dev/featured/fonts/) containing [Google Font: 
Montserrat]https://fonts.google.com/specimen/Montserrat/about?query=Montserrat).

The old posters and signs in the traditional Montserrat 
neighborhood of Buenos Aires inspired Julieta Ulanovsky 
to design this typeface and rescue the beauty of urban 
typography that emerged in the first half of the twentieth 
century. As urban development changes that place, it will 
never return to its original form and loses forever the 
designs that are so special and unique. The letters 
that inspired this project have work, dedication, care,
color, contrast, light and life, day and night! 
These are the types that make the city look so beautiful.
The Montserrat Project began with the idea to rescue what 
is in Montserrat and set it free under a libre license, 
the SIL Open Font License.



Designers: [Julieta Ulanovsky](https://github.com/JulietaUla/Montserrat), Sol Matas, Juan Pablo del Peral,
Jacques Le Bailly

## How To Use This Font In Your fastn Package:

[Read the docs and demo](https://fifthtry.github.io/montserrat).

TLRD:

Include fifthtry.github.io/raleway-font package into `FASTN.ftd` file:

```ftd
;-- fpm.dependency: fifthtry.github.io/montserrat
```

Inside your `FASTN/config.ftd` use the font:

```ftd
;-- import: fifthtry.github.io/montserrat/assets as montserrat

;-- fpm.type.headline-small: $montserrat.fonts.Montserrat
```

Now if in any file you do:

```ftd
;-- ftd.text:
role: $fpm.type.headline-small
```

You will see the `Montserrat` font.

## 👀 Want to learn more?

Feel free to check [our documentation](https://fpm.dev/) or jump into our [FifthTry Discord 
server](https://discord.gg/bucrdvptYd).

## License

Since Montserrat  Font is under [OFL](https://fonts.google.com/specimen/Montserrat/about?query=Montserrat), this FASTN wrapper is also
under [OFL](LICENSE).




