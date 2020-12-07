# semantic-math-editor

[![npm](https://img.shields.io/npm/v/semantic-math-editor)](https://www.npmjs.com/package/semantic-math-editor)

Editing math formulas on the web 

Official site: https://math-editor.com/semanticEditor.html

Developer Version Installation:

```
   npm i semantic-math-editor
```

Getting started:


*HTML:*


```
<html>

<head>
    <meta http-equiv="Content-Type" content="text/html" charset="utf-8" />
    <meta name="viewport" content="width=device-width">
    
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.10.2/dist/katex.min.css"
          integrity="sha256-uT5rNa8r/qorzlARiO7fTBE7EWQiX/umLlXsq7zyQP8=" crossorigin="anonymous">
  
    <script src="node_modules/semantic-math-editor/index.bundle.js"></script> 
    
</head>
<body>
   <div id="editor"/> 
   
   <script>
      let editor = SemanticMathEditor.createEditor(document.getElementById("editor"));
   </script>
</body>
```

*Typescript:*

```
import {createEditor} from "semantic-math-editor";

const editor = createEditor(document.getElementById('my-id');

```


