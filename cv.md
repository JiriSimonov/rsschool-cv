# Curriculum vitae
* ## George Simonov 
* ## Contacts
  + Phone: +79823846916
  + Emal: jirisimonov@gmail.com
  + Discord: Shaperx#1702
* Info
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
* Work
* Education
* ## Languages
  + English - pre-intermediate; 
  + Russian - native;
  + Czech - upper-intermediate.
