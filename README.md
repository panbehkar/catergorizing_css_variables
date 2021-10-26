# Categorizing CSS variables 
Categorizing CSS variables is not a new feature or best practice in CSS. You can't find anything about this title on the internet. It's only my own experience, and it may not be the right thing to do :)

Using variables in the browser's inspector can be confusing when the number of CSS variables increases. So I did a little trick using a variable name:

```css
:root {
  --_______________Palette_______________--: ;
  --primary: CornflowerBlue;
  --secondary: LightSkyBlue;
  --success: Green;
  --danger: Red;
  --warning: Orange;
  --info: MediumPurple;
  --dark: MidnightBlue;
  --light: AliceBlue;
  --_______________Typography_______________--: ;
  --font-family: Arial;
  --font-size-sm: 15px;
  --font-size-md: 17px;
  --font-size-lg: 20px;
  --font-weight-thin: 300;
  --font-weight-regular: 500;
  --font-weight-bold: 700;
  --line-height: 1.5;
  --_______________MediaQueries_______________--: ;
  --xs: 0;
  --sm: 576px;
  --md: 768px;
  --lg: 992px;
  --xl: 1200px;
}
```
