#### CSS Selector
```
selector {
  css ruleset
  property-name : "value";
}
```

- Universal Selector (*)
```css
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
```

- Class selector  denoted by dot followed by the class name
  ```html
    <p class="my-class">dgggdggddgdgdgdgdggdgdg</p>
  ```
  ```css
     .my-class{
      width: 300px;
     }
  ```

- Id Selector is denoted with hash symbol(#)
  for instance
  ```html
    <p id="my-id">dgggdggddgdgdgdgdggdgdg</p>
  ```
  ```css
     #my-id{
      wdth: 300px;
     }
  ```
- Class Element Selector

  ```html
  <div>
    <div class="top">
      <h3>title</h3>
      <p>first para</p>
    </div>
    <div class="bottom">
      <h3>title</h3>
      <p>first para</p>
    </div>
  </div>
  ```
  ```css
     .bottom h3{
      color: red;
     }
  ```

- Grouping Selector
  ```css
      h1, 
      h2, 
      h3, 
      h4, 
      h5, 
      h6, 
      p, 
      a{
        color: white;
        font-family: monospace;
      }
  ```

- Styling Attributes (Applying styles to HTML Attributes) (e.g href)
  
- Pseudo-Classes in CSS

Examples are :hover, :disabled, :required, :checked, :visited e. t. c

- Pseudo-elements in CSS