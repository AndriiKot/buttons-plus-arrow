
<a id=top></a>

# Cat Photo App

<details>
      <summary>
        <h4>Follow Links Steps</h4>
      </summary>
       
<table>
  <thead>
    <tr><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__00__title_" target="_self">Step 0</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__01__step__" target="_self">Step 1</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__02__step__" target="_self">Step 2</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__03__step__" target="_self">Step 3</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__04__step__" target="_self">Step 4</a></th><tr><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__05__step__" target="_self">Step 5</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__06__step__" target="_self">Step 6</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__07__step__" target="_self">Step 7</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__08__step__" target="_self">Step 8</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__09__step__" target="_self">Step 9</a></th><tr><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__10__step__" target="_self">Step 10</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__11__step__" target="_self">Step 11</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__12__step__" target="_self">Step 12</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__13__step__" target="_self">Step 13</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__14__step__" target="_self">Step 14</a></th><tr><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__15__step__" target="_self">Step 15</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__16__step__" target="_self">Step 16</a></th><th><a href="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp//tree/main/steps/__17__step__" target="_self">Step 17</a></th></tr>
  </thead>
  <tbody>
  </tbody>
</table>
</details>


<details>
      <summary>
        <h4>Description of the Task</h4>
      </summary>
       <h3>Step  17</h3>

<section>
<p>In previous steps you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.</p>
<p>Here is an example of turning an image into a link:</p>
<details class="code-details" open=""><summary class="code-details-summary">Example Code</summary><pre class="language-html" tabindex="0" role="region" aria-label="HTML code example"><code class="language-html"><span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>a</span> <span class="token attr-name">href</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>example-link<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
  <span class="token tag"><span class="token tag"><span class="token punctuation">&lt;</span>img</span> <span class="token attr-name">src</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>image-link.jpg<span class="token punctuation">"</span></span> <span class="token attr-name">alt</span><span class="token attr-value"><span class="token punctuation attr-equals">=</span><span class="token punctuation">"</span>A photo of a cat.<span class="token punctuation">"</span></span><span class="token punctuation">&gt;</span></span>
<span class="token tag"><span class="token tag"><span class="token punctuation">&lt;/</span>a</span><span class="token punctuation">&gt;</span></span>
</code></pre></details>
<p>Turn the image into a link by surrounding it with necessary element tags. Use <code>https://freecatphotoapp.com</code> as the anchor's <code>href</code> attribute value.</p>
</section>
</details>

<h4>preview</h4>
    <img src="https://github.com/AndriiKot/Desing___Cat_Photo_App___freeCodeCamp/blob/main/images/previews/preview_step17.png" alt="preview_step17">
  
<table>
  <thead>
      <tr><th height=33 width=100>HTML5</th>
  </thead>
  <tbody>
      <tr><td height=100 width=100><a href=https://html.spec.whatwg.org/multipage/ target="_self"><img src=https://github.com/AndriiKot/iconsSVG_and_linksDocs/blob/main/svg/html.svg alt=HTML5></a></td>
  </tbody>
</table>

[back to top](#top)



<details open>
  <summary>
    <h4>index.html</h4>
  </summary>



```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Cat Photo App</title>
  </head>
  <body>
    <main>
      <h1>CatPhotoApp</h1>
      <h2>Cat Photos</h2>
      <p>Everyone loves <a href="https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg">cute cats</a> online!</p>
      <p>See more <a href="https://freecatphotoapp.com" target="_blank">cat photos</a> in our gallery.</p>
      <a href="https://freecatphotoapp.com">
        <img src="https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg" alt="A cute orange cat lying on its back">
      </a>
    </main>
  </body>
</html>

```



[back to top](#top)


</details>