## A Simple 2 Layers UI Element With Lite Swap Animation. 

#### Live Demo
https://kubbafox.github.io/3DLayersLite/

#### A few features
- Click & Swap Layers
- Fade The Visited Layer
- Scroll Down & Change Layer Title to Vetical Position
- Clickable Vertical Positon Title

#### How to use it
Simply use HTML Tags and import JS/CSS files to your project. 

```HTML
<div class="evo_c_multiLayers_container" id="evo_js_multiLayers_container">
  <section class="evo_c_multiLayers_layer evo_js_multiLayers_layer" id="evo_js_multiLayers_layer_1">
    <div class="evo_c_multiLayer_header" id="evo_js_multiLayers_layer_header_1">
      Layer Header 1
    </div>
   </section>
   <section class="evo_c_multiLayers_layer evo_js_multiLayers_layer" id="evo_js_multiLayers_layer_2">
    <div class="evo_c_multiLayer_header" id="evo_js_multiLayers_layer_header_2">
      Layer Header 2
    </div>
   </section>
</div>   
```
There are a few pre-defined text blocks for you to use **after** the `<div class="evo_c_multiLayer_header">` tag


```HTML
    <div class="evo_c_multiLayer_title">
      Accumsan pellentesque
    </div>
```

```HTML
    <div class="evo_c_multiLayer_content">
      Accumsan pellentesque
    </div>
```

```HTML
    <div class="evo_c_multiLayer_bullet_point">
      Accumsan pellentesque
    </div>
```

Or you can create your own `div` tags based on your need. 
**Please do not overwirte the `left` value in `.evo_c_multiLayers_container section div` css properties**
