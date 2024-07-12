# HTML FUNDERMENTALS

# INTRO TO HTML

- Hyper Text Markup Language
- It is a markup language, that is used to structure and describe the content of the webpage
- Not a programming language
- It consists of some elements that describes different types of content:
  paragraphs, links, headings,images, videos and etc.
- Browsers understand HTML and render HTML code as websites

# Anatomy of HTML element

- <p> HTML is a markup language</p>
- from starting tag to end tag together its called elemeent
- opening tag -> name of the element wrapped in < and >
- content -> content of the element, in this example text. But it might be another element (child element).
  some elemtns have no content ( eg. <img> )
- closing tag -> Same as opening tag, but with a /. when element has no content, its omitted.

# HTML Document structure

- imported required assets and contents
- added new file index.html
- Creating a basic Blog site
- we have 5 tags, that make the document structure
- DOCTYPE html, html, head, body, footer

# Text Elements

- Headings (h1, h2, h3, h4, h5, h6)
- Paragraphs (p)
- bold (strong , b)
- italic (em, i)
- list items (ul, li)
- anchor (a)

# Semantic Elements

- header
- main
- article
- aside
- footer

# CSS

- cascading Style Sheets.
- CSS describes the visual style and presentation of the content written in HTML.
- selector - a tag or class or id that has declaration box
- declaration - is a property and value pair
- Rule - a selector with bunch of properties together.

# conflicts between selectors.

- when multiple selectors selecting same element.
- all of the properties and rules are applied.
- but there are conflicting properties.
- highest priority - declrations marked as !important.
- inline style (style attribute in HTML)
- from class, id and element selector, id has the highest priority.
- if there are multiple id selectors, then the last one is applied.
- after id, next priority is -> class or psuedo class -> if multiple class or psuedo code present then the last one gets applied.
- next is elemnt selector
- last one is universal selector - lowest priority.

# inheritance and universal selector.

- only properties related to text, is been inherited...
- inherited value can be overriden by using same property with diffrent value easily.
