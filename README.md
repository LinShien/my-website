## HTML tag cheatsheet

- `<div>`: The `<div>` tag is used as a container for HTML elements - which is then styled with CSS or manipulated with JavaScript. And any sort of content can be put inside the `<div>` tag! 

        <section>
            <div>
                This is content inside <div> container.
            </div>
        </section>

<br>

- `<section>`: The `<section>` tag defines a 'actual' section in a document which unlike `<div>` just define wrapper.

<br>

- `<link>`: The `<link>` tag defines the relationship between the current document and an external resource. This tag is most often used to link to external style sheets.

    	<link rel="preconnect" href="https://fonts.gstatic.com">

<br>

- `<meta>`: `<meta>` tags always go inside the `<head>` element, and are typically used to specify character set, page description, keywords, author of the document, and viewport settings.

        <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, minimum-scale=1" />

## CSS property cheatsheet

- `@media`: The @media rule, make it possible to define different style rules for different media types.

<br>

- `display`: The `display` property specifies if/how an element is displayed.
    
        .greeting-wrapper {
            display: grid;
        }

<br>

- `Margin vs Padding`: Basically, a margin is the space around an element and padding refers to the space between an element and the content inside it.
    ![aa](https://blog.hubspot.com/hs-fs/hubfs/HubSpot%20%7C%20CSS%20Margin%20vs%20Padding-1.jpeg?width=1500&name=HubSpot%20%7C%20CSS%20Margin%20vs%20Padding-1.jpeg)

<br>

- `margin: auto`: You can set the margin property to auto to horizontally center the element within its container. The element will then take up the specified width, and the remaining space will be split equally between the left and right margins