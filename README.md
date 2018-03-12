# Simple buttons with HTML and CSS

Simple colorful buttons with web safe colors

[Demo](http://jerrythimothy.bigjapps.com/simple-buttons/) - Click the link for the list of colorful buttons

## Description

* A good bunch of CSS classes with 216 Web Safe Colors.
* Sharp Rectangular Button
* Blunt Rectangular Button
* Disabled Button
* Transparent Button
* Capsule Shaped Button
* Circular Button
* Button With Image
* Button With Image and Text
* Extra Small Button
* Small Button
* Medium Button
* Large Button
* Extra Large Button
* Block Level Button

## Getting Started

Just take a look at the HTML and the CSS files for implementation

### Example Usage

```
<button class="button button-large bg-cc3300">#cc3300</button>
```

### Sample CSS Code
```
.button {
    margin: 6px 0;
    border: none;
    border-radius: 0;
    outline: none;
    font-weight: 400;
    text-align: center;
    white-space: nowrap;
    vertical-align: middle;
    line-height: 100%;
    text-align: center;
    cursor: pointer; 
    color: #ffffff;
}

.button > img {
    vertical-align: middle;
}

.button:hover {
    -webkit-filter: brightness(110%);
    filter: brightness(110%);
}

.button:disabled {
    -webkit-filter: brightness(75%);
    filter: brightness(75%);
    cursor: not-allowed;
}

.button:active {
    box-shadow: none;
}

.button-block {
    display: block;
    width:100%;
}

.button-blunt {
    border-radius: 4px;
}

.button-round {
    border-radius: 50%;
}

.button-x-large {
    height: 60px;
    font-size: 26px;
    box-shadow: inset 0 -3px 0 0 rgba(0, 0, 0, 0.2);
}

.button-x-large.button-capsule {
    border-radius: 30px;
}

.button-x-large:active {
    line-height: 60px;
}

.button-trans {
    border: 1px solid;
    background: transparent;
    box-shadow: none;
}
```

### Output

![alt text](http://jerrythimothy.bigjapps.com/simple-buttons/output.png)


### Compatility on Hover Effect

![alt text](http://jerrythimothy.bigjapps.com/simple-buttons/compatibility.png)
