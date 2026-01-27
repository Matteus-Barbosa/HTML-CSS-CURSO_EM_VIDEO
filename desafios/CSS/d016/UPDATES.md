## Responsiveness

Use more relative units (%, vw, vh, auto);

## Semantic vs Style
```css
html, body { /*set to 100% of viewport units, facilitating to position their children on layout*/
    height: 100vh;
    width: 100vw;
}

div.card { /*based on html and body percent viewport units*/
    width: 80vw;
    height: 70vh; 
}

div.card > div.img { /*same technique concept*/
    background-image: url(../img/dog.png);
    float: right;
    width: 50%;
    height: 100%;
}
```

