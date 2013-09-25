# GitHub Markdown Kitchen Sink

| A large set of examples of what works in README.md files on GitHub.

[View README.md raw file](https://raw.github.com/adamschwartz/github-markdown-kitchen-sink/master/README.md)

## Examples with Code

<table>
  <tr><td>Code</td><td>Preview</td></tr>
  
  <!--- Paragraphs -->
  <tr>
    <td colspan="2">Paragraph</td>
  </tr>
  <tr>
    <td>
      <pre><code>This is a paragraph.</code></pre>
    </td>
    <td>This is a paragraph.</td>
  </tr>
  
  <!--- Headers -->
  <tr>
    <td colspan="2">Headers (Sextext-style)</td>
  </tr>
  <tr>
    <td>
<pre><code>Header 1
========

Header 2
--------</code></pre>
    </td>
    <td>
      <h1>Header 1</h1>
      <h2>Header 2</h2>
    </td>
  </tr>
  <tr>
    <td colspan="2">Headers (Atx-style)</td>
  </tr>
  <tr>
    <td>
<pre><code># Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6</code></pre>
    </td>
    <td>
      <h1>Header 1</h1>
      <h2>Header 2</h2>
      <h3>Header 3</h3>
      <h4>Header 4</h4>
      <h5>Header 5</h5>
      <h6>Header 6</h6>
    </td>
  </tr>
  <tr>
    <td colspan="2">Headers (Atx-style closed)</td>
  </tr>
  <tr>
    <td>
<pre><code># Header 1 #
## Header 2 ##
### Header 3 ###
#### Header 4 ####
##### Header 5 #####
###### Header 6 #####</code></pre>
    </td>
    <td>
      <h1>Header 1</h1>
      <h2>Header 2</h2>
      <h3>Header 3</h3>
      <h4>Header 4</h4>
      <h5>Header 5</h5>
      <h6>Header 6</h6>
    </td>
  </tr>
  
  <!--- Blockquotes -->
  <tr>
    <td colspan="2">Blockquote</td>
  </tr>
  <tr>
    <td>
      <pre><code>> Lorem ipsum dolor sit amet [...]</code></pre>
    </td>
    <td>
      <blockquote>
        Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
        Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
        viverra nec, fringilla in, laoreet vitae, risus.
      </blockquote>
    </td>
  </tr>
  <tr>
    <td colspan="2">Blockquote with nested elements</td>
  </tr>
  <tr>
    <td>
      <!--- Code exmaple -->
      <pre><code>> ## This is a header.
> 1. This is the first list item.
> 2. This is the second list item.
> 
> Here's some example code:
> 
>     Markdown.generate();</code></pre>
      <!--- End code exmaple -->
    </td>
    <td>
      <blockquote>
        <h2>This is a header.</h2>
          <ol>
            <li>This is the first list item.</li>
            <li>This is the second list item.</li>
          </ol>
          <p>Here's some example code:</p>
          <pre><code>Markdown.generate();</code></pre>
      </blockquote>
    </td>
  </tr>
  
  <!--- Lists -->
  <tr>
    <td colspan="2">List</td>
  </tr>
  <tr>
    <td>
<table><tr><td>
<pre><code>- Red
- Green
- Blue</code></pre>
</td><td>
<pre><code>+ Red
+ Green
+ Blue</code></pre>
</td><td>
<pre><code>* Red
* Green
* Blue</code></pre>
</td></tr></table>
    </td>
    <td>
      <ul>
        <li>Red</li>
        <li>Green</li>
        <li>Blue</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td colspan="2">Ordered List</td>
  </tr>
  <tr>
    <td>
<pre><code>1. Red
1. Green
1. Blue</code></pre>
    </td>
    <td>
      <ol>
        <li>Red</li>
        <li>Green</li>
        <li>Blue</li>
      </ol>
    </td>
  </tr>

  <!-- Code blocks -->
  <tr>
    <td colspan="2">Ordered List</td>
  </tr>
  <tr>
    <td>
<pre><code>Normal paragraph.
    Code</code></pre>
    </td>
    <td>
      <p>Normal paragraph.</p>
      <pre><code>Code</code></pre>
    </td>
  </tr>
</table>
