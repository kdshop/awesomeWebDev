# awesomeWebDev
Cool snippets for your web development.
### Recipe for responsive font system from [100% Responsive Typography System using a Modular Scale by Ricardo Zea](https://www.codementor.io/ricardozea/100-responsive-typography-system-using-a-modular-scale-s5rhft58g)

```css
/* Modular Scale located here: https://www.modularscale.com/?1,1140,12&em&1.3 */

body {
  font-family: Arial, Helvetica, sans-serif;
  font-size: calc(12px + 0.35vw); /* Responsive base font size */
  line-height: calc(12px + 1.05vw); /* Responsive Vertical Rhythm */
}

.main-ctnr {
  width: 100%; /* For small screens */
  max-width: 1140px; /* For large screens */
  margin: auto; /* Center the container in the viewport */
}

h1 {
  font-size: 1.912em;
  line-height: calc(18px + 1.8vw); /* Responsive Vertical Rhythm */
}

h2 {
  font-size: 1.616em;
  line-height: calc(18px + 1vw); /* Responsive Vertical Rhythm */
}

h3 {
  font-size: 1.471em;
  line-height: calc(18px + 0.7vw); /* Responsive Vertical Rhythm */
}

h4 { font-size: 1.3em; }
h5 { font-size: 1.243em; }
h6 { font-size: 1.132em; }

h4, h5, h6 { 
  line-height: calc(18px + .2vw); /* Responsive Vertical Rhythm */
}

h1, h2, h3, h4, h5, h6 {
  margin: calc(12px + 1.05vw) 0; /* Responsive margins */
}
```
