# Basic Web Techniques - Lists and Tables

## Html for Lists

1. Start tags for
   - an ordered list `<ol>`
   - an unordered list: `<ul>`
   - a description list: `<dl>`
   - a list item: `<li>`
   - a description term: `<dt>`
   - a description data: `<dd>`

## Css for Lists

1. Make bullet a square:

   ```
   ol {
      list-style-type: square;
   }
   ```

2. Make bullet an image named "my-bullet.png":

   ```
   ol {
      list-style-image: url("my-bullet.png");
   }
   ```

3. Make bullet an uppercase roman number:

   ```
   ol {
      list-style-type: upper-roman;
   }
   ```

4. Set bullet position to be inside the list item's text flow:
   
   ```
   ol {
      list-style-position: inside;
   }
   ```

5. Set bullet position to be outside the list item's text flow:

   ```
   ol {
      list-style-position: outside;
   }
   ```

## Html for Tables

1. Start tags for
   - a table: `<table>`
   - a table row: `<tr>`
   - a table header: `<thead>`
   - a table header cell: `<th>`
   - a table body: `<tbody>`
   - a table cell: `<td>`
   - a table footer: `<tfoot>`
   - a table footer cell: `<td>`

## Css for Tables

1. Black dotted border of 1 px width: `border: 1px dotted black;`
2. Solid border of 1 px width having a red color and rounded corners: `border: 1px solid red; border-radius: 5px;`
3. Merge the borders of table cells so that they appear as one line: `border-collapse: collapse;`