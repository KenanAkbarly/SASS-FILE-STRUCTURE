# Sass File Structure

Bu repoda [Sass](https://sass-lang.com/) istifadə olunan layihələr üçün sadə struktur yaratmışam.

## Struktur

- abstracts

  - `_functions.scss` -> İstifadəçi tərəfindən müəyyən edilmiş funksiyaları əhatə edəcək.
  - `_mixins.scss` -> Sizin mixinlərinizi əhatə edəcək. <br />
  - `_variables.scss` -> Sizin dəyişənlərinizi əhatə edəcək.
  
- base
  
  - `_animations.scss` -> Sizin animasiyalarınızı əhatə edəcək.
  - `_base.scss` -> Defolt elementlər üçün stilləriniz əhatə edəcək.
  - `_typography.scss` -> Text stilləriniz əhatə edəcək. məsələn: font-family, font-size, color, ....
  - `_utilities.scss` -> Custom yaratdığımız utilitləri əhatə edəcək.

- components

      Komponent stillərini bura əlavə edin, hər bir komponent üçün ayrı file yaratmağa üstünlük verin.

- layout

      header, footer, navigation kimi layout'larınızı bu file içinə əlavə edin.

- pages

    Hər bir səhifəmizin stili isə pages file'na əlavə olunur.

- `main.scss`

      Bütün folderimizdəki scss file'ları isə sonda main.scss-ə import olunur.

## Qeyd

> Bu struktur sadə və çox istifadə olunan strukturlardan biridir, strukturu özünüzə uyğun bir şəkildə dəyişə bilərsiniz.
