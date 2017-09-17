# Queries
### A CSS media query cheatmap.

* [iPad](#ipad)
* [iPad 3 & 4 (Retina)](#ipad-3--4-retina)
* [iPad 1 & 2 (Non-Retina)](#ipad-1--2-non-retina)
* [iPad mini](#ipad-mini)
* [iPhone 6 & 7](#iphone-6--7)
* [iPhone 6 & 7 Plus](#iphone-6--7-plus)
* [iPhone 5 & 5S](##iphone-5--5s)
* [iPhone 2G & 3G & 4 & 4S](#iphone-2g--3g--4--4s)

## iPad
### Portrait and Landscape
```css
@media only screen
and (min-device-width: 768px)
and (max-device-width : 1024px)  { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : portrait) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : landscape) { /* STYLES GO HERE */}
```
## iPad 3 & 4 (Retina)
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px)
and (-webkit-min-device-pixel-ratio: 2) { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : portrait)
and (-webkit-min-device-pixel-ratio: 2) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : landscape)
and (-webkit-min-device-pixel-ratio: 2) { /* STYLES GO HERE */}
```

## iPad 1 & 2 (Non-Retina)
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (-webkit-min-device-pixel-ratio: 1){ /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : portrait) 
and (-webkit-min-device-pixel-ratio: 1) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : landscape)
and (-webkit-min-device-pixel-ratio: 1)  { /* STYLES GO HERE */}
```

## iPad mini
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px)
and (-webkit-min-device-pixel-ratio: 1)  { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : portrait)
and (-webkit-min-device-pixel-ratio: 1)  { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 768px) 
and (max-device-width : 1024px) 
and (orientation : landscape)
and (-webkit-min-device-pixel-ratio: 1)  { /* STYLES GO HERE */}
```

## iPhone 6 & 7
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 375px) 
and (max-device-width : 667px) { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 375px) 
and (max-device-width : 667px) 
and (orientation : portrait) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 375px) 
and (max-device-width : 667px) 
and (orientation : landscape) { /* STYLES GO HERE */}
```

## iPhone 6 & 7 Plus
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 414px) 
and (max-device-width : 736px) { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 414px) 
and (max-device-width : 736px) 
and (orientation : portrait) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 414px) 
and (max-device-width : 736px) 
and (orientation : landscape) { /* STYLES GO HERE */}
```

## iPhone 5 & 5S
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 568px) { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 568px) 
and (orientation : portrait) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 568px) 
and (orientation : landscape) { /* STYLES GO HERE */}
```

## iPhone 2G & 3G & 4 & 4S
### Portrait and Landscape
```css
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 480px) { /* STYLES GO HERE */}
```

### Portrait
```css
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 480px) 
and (orientation : portrait) { /* STYLES GO HERE */ }
```

### Landscape
```css
@media only screen 
and (min-device-width : 320px) 
and (max-device-width : 480px) 
and (orientation : landscape) { /* STYLES GO HERE */}
```