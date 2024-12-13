To center an absolute element within a relative container, you would make use of the following properties

## HTML
```html
    <div class="relative">
        <div class="absolute">Hey</div>
    </div>
```

```css
.relative {
    position: relative;
}

.absolute {
    position: absolute;
    left: 50%;
    top: 50%;
    transform: translate(-50%, -50%);
}
```


No explanation on here, it works ;)