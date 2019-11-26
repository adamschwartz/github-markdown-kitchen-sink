# GitHub Markdown Kitchen Sink

A large collection of code samples which have been tested against GitHub's markdown parser... so you don't have to.

#### Resources

##### This Repo

- README.md ([preview](https://github.com/adamschwartz/github-markdown-kitchen-sink/blob/master/README.md), [raw](https://raw.github.com/adamschwartz/github-markdown-kitchen-sink/master/README.md)) – this file
- TEST.md ([preview](https://github.com/adamschwartz/github-markdown-kitchen-sink/blob/master/TEST.md), [raw](https://raw.github.com/adamschwartz/github-markdown-kitchen-sink/master/TEST.md)) — used to test the examples from this file, which are pre-generated

##### Markdown

- [Original Markdown Syntax](http://daringfireball.net/projects/markdown/syntax) from John Gruber
- [GitHub-Flavored Markdown](https://help.github.com/articles/github-flavored-markdown) from GitHub

## Code Examples with Preview

### Block Elements

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
<pre><code>1. Buy flour and salt
1. Mix together with water
1. Bake</code></pre>
    </td>
    <td>
      <ol>
        <li>Buy flour and salt</li>
        <li>Mix together with water</li>
        <li>Bake</li>
      </ol>
    </td>
  </tr>

  <!-- Code blocks -->
  <tr>
    <td colspan="2">Code Block</td>
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

  <!-- Horizontal rules -->
  <tr>
    <td colspan="2">Horizontal Rules</td>
  </tr>
  <tr>
    <td>
<pre><code>* * *

***

*****

- - -

---------------------------------------</code></pre>
    </td>
    <td>
      <hr/>
      <hr/>
      <hr/>
      <hr/>
      <hr/>
    </td>
  </tr>
</table>

### Inline Elements

<table>
  <tr><td>Code</td><td>Preview</td></tr>

  <!--- Links -->
  <tr>
    <td colspan="2">Links</td>
  </tr>
  <tr>
    <td>
      <pre><code>This is [an example](http://example.com "Example") link.

[This link](http://example.com) has no title attr.

This is [an example] [id] reference-style link.

[id]: http://example.com "Optional Title"</code></pre>
    </td>
    <td>
      <p>This is <a href="http://example.com" title="Example">an example</a> link.</p>
      <p><a href="http://example.com">This link</a> has no title attr.</p>
      <p>This is <a href="http://example.com" title="Optional Title">an example</a> reference-style link.</p>
    </td>
  </tr>

  <!--- Emphasis -->
  <tr>
    <td colspan="2">Emphasis</td>
  </tr>
  <tr>
    <td>
      <pre><code>*single asterisks*

_single underscores_

**double asterisks**

__double underscores__</td>
    <td>
      <p><em>single asterisks</em></p>
      <p><em>single underscores</em></p>
      <p><strong>double asterisks</strong></p>
      <p><strong>double underscores</strong></p>
    </td>
  </tr>

  <!--- Code -->
  <tr>
    <td colspan="2">Code</td>
  </tr>
  <tr>
    <td>
      <pre><code>This paragraph has some `code` in it.</td>
    <td>
      <p>This paragraph has some <code>code</code> in it.</p>
    </td>
  </tr>

  <!--- Images -->
  <tr>
    <td colspan="2">Image</td>
  </tr>
  <tr>
    <td>
      <pre><code>![Alt Text](https://get.svg.workers.dev/?h=50&w=200&f=rgba(0,0,0,.1) "Image Title")</td>
    <td>
      <p><img src="https://get.svg.workers.dev/?h=50&w=200&f=rgba(0,0,0,.1)" title="Image Title" alt="Alt Text" /></p>
    </td>
  </tr>
</table>
