# Curriculum vitae
* ## George Simonov 
* ## Contacts
  + Phone: +79823846916
  + Emal: jirisimonov@gmail.com
  + Discord: Shaperx#1702
* ## About me
  During my studies at Charles University, an unprecedented desire for knowledge arose in me. I was very interested in how the web is structured and among the many   options for interacting with it I chose the front-end. Now I develop in this direction, accumulating knowledge and honing skills
* ## Skills
  + ### HTML
    - PUG/JADE
  + ### CSS
    - SASS(SCSS)
    - LESS
  + ### JS
    - React 
  + ### PHP
  + ### Graphic editors
    - Figma
    - Adobe Photoshop
    - Adobe XD
* ## Code example
```
export const priceFilter = (goods, minValue, maxValue) => {
    return goods.filter((goodsItem) => {
        if (minValue === '' && maxValue === '') {
            return goodsItem;
        } else if (minValue !== '' && maxValue !== '') {
            return goodsItem.price >= +minValue && goodsItem.price <= +maxValue;
        } else if (minValue !== '' && maxValue === '') {
            return goodsItem.price >= +minValue;
        } else if (minValue === '' && maxValue !== '') {
            return goodsItem.price <= +maxValue;
        }
    });
}
```
* ## Works
  + [TOXIN](https://github.com/JiriSimonov/TOXIN/tree/Styles) (PUG, SASS, JS)
  + [O-ZONE](https://github.com/JiriSimonov/O-ZONE) (HTML, CSS, JS)
* ## Courses
  + HTML Academy
  + Skillbox
  + Stepik
  + W3schools
* ## Languages
  + English - pre-intermediate
  + Russian - native
  + Czech - upper-intermediate
