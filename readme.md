- {
  box-sizing: border-box;
  color: inherit;
  text-decoration: none;
  }

@font-face {
font-family: Circular;
src: url("https://sp-bootstrap.global.ssl.fastly.net/8.12.1/fonts/circular-light.woff2")
format("woff2"),
url("https://sp-bootstrap.global.ssl.fastly.net/8.12.1/fonts/circular-light.woff")
format("woff");
font-weight: 300;
font-style: normal;
}

:root {
/_COLORS_/
--primary-color: black;
--secondary-color: #4bb84a;
--light-color: white;
/_FONTS_/
--primary-font: Circular, Arial, Helvetica, sans-serif;
}

.wrapper {
max-width: 1200px;
margin: auto;
width: 100%;
border: 1px solid green;
padding: 15px;
}

html {
font-family: var(--primary-font);
font-size: 16px;
}

.menu {
list-style-type: none;
padding: 0px;
}

.header-menu li:nth-child(3):after {
content: "|";
}

/_ MEDIAQUERIES _/

/_ Tablet _/

@media all and (min-width: 768px) {
}

/_ Desktop _/
@media all and (min-width: 1200px) {
}
