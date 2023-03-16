#Front End Developer Interview Questions


## HTML& HTML5 Interview Questions:

1. ### What is HTML?
    HTML stands for Hypertext Markup Language. It is the standard markup language used for creating and designing web pages and applications. HTML uses a combination of tags, attributes, and elements to structure the content and define its meaning. The primary purpose of HTML is to create a structure for content that can be displayed in web browsers. This structure includes text, images, videos, links, and other types of multimedia content. HTML is essential for creating web pages and is widely used by web developers and designers around the world.HTML stands for Hypertext Markup Language. It is the standard markup language used for creating and designing web pages and applications. HTML uses a combination of tags, attributes, and elements to structure the content and define its meaning. The primary purpose of HTML is to create a structure for content that can be displayed in web browsers. This structure includes text, images, videos, links, and other types of multimedia content. HTML is essential for creating web pages and is widely used by web developers and designers around the world.

2. ### What is the difference between HTML & HTML 5 ?
    HTML is the original markup language used for creating and designing web pages, while HTML5 is the latest version of HTML. Here are some of the key differences between HTML and HTML5:

    1. Multimedia support: HTML has limited support for multimedia content, while HTML5 offers better support for audio, video, and other types of multimedia.

    2. Form controls: HTML5 offers new form controls, such as date pickers, sliders, and range controls, which make it easier to create interactive forms.

    3. Canvas and SVG: HTML5 includes support for the Canvas and SVG graphics APIs, which enable developers to create complex, interactive graphics and animations directly in the browser.

    4. Local storage: HTML5 provides a new way to store data locally on the user's device, using the Local Storage API.

    5. Semantic markup: HTML5 includes new semantic markup elements, such as `<article>`,`<section>`,`<nav>` which provide a clearer structure for web content and improve accessibility.

    Overall, HTML5 offers new features and capabilities that make it easier to create modern, interactive web pages and applications.

3. ### Why do we need `<!DOCTYPE html>` in HTML?
    The DOCTYPE declaration in HTML is used to inform the web browser about the version of HTML that the web page is written in. It is placed at the top of an HTML document before the `<html>` tag.

    The DOCTYPE declaration helps the web browser to render the web page correctly and avoid rendering errors. The DOCTYPE declaration defines the rules and elements that the web browser should use to render the page, such as the syntax and character encoding.

    For example, the DOCTYPE declaration for HTML5 is:
        `<!DOCTYPE html>`
    This tells the browser that the document is written in HTML5 and should be rendered according to the HTML5 specification.

    Without a DOCTYPE declaration, the web browser may not be able to render the web page correctly, resulting in display errors or even a broken page.


4. ### Purpose of `<title>` tag:

    The title tag in HTML is used to define the title of the document, which appears in the browser tab when the page is opened. The title tag is also used by search engines to display the title of the page in the search results.


5. ### Purpose of `<meta ...>` tag:

    The meta tag in HTML is used to provide metadata about the document, such as keywords, description, author, and viewport settings for mobile devices. This information is used by search engines, browsers, and other web applications.


6. ### Scemantic In HTML:

    Semantic HTML is a way of writing HTML that focuses on the meaning and purpose of the content, rather than just its appearance. Semantic HTML uses specific tags that describe the type of content they contain, such as `<header>`, `<nav>`, `<article>`, `<section>`, `<aside>`, and `<footer>`. This makes the content more accessible to users with disabilities, and also helps search engines and other web applications to understand and process the content more accurately.

7. ### Types of lists in HTML:

    There are three types of lists in HTML:

    1. Unordered lists: created using the `<ul>` tag, and each list item is marked with the `<li>` tag. They display a bullet or other marker next to each item.
    2. Ordered lists: created using the `<ol>` tag, and each list item is marked with the `<li>` tag. They display a number or other marker next to each item.
    3. Definition lists: created using the <dl> tag, and each item consists of a term (defined using the `<dt>` tag) and its definition (defined using the `<dd>` tag).

8. ### `alt` attribute in HTML:
    The alt attribute in HTML is used to provide alternative text for images. This text is displayed in place of the image if it cannot be loaded, or if the user is using a screen reader to access the content. The alt text should describe the content of the image in a concise and accurate manner.

9. ### `id` and `class` attribute in HTML:
    The id attribute in HTML is used to uniquely identify an element on the page, and can be used to link to that element from other parts of the page. The id value must be unique within the document.

    The class attribute in HTML is used to group elements that share a common style or purpose. Multiple elements can share the same class name, and the class name can be used to apply styles or scripting to all of those elements at once.

10. ### `href` attribute purpose:
    The href attribute in HTML is used to specify the destination of a hyperlink, which can be a URL, an email address, or an anchor link within the same document. The href attribute is used in conjunction with the `<a>` tag to create hyperlinks. When the user clicks on a hyperlink, the browser navigates to the URL specified in the href attribute.

## CSS Interview Questions:

1. ### What is CSS?
    CSS stands for Cascading Style Sheets. It is a style sheet language used for describing the presentation of a document written in HTML or XML, including colors, layout, and fonts. CSS allows web developers to separate the presentation of a document from its content, making it easier to maintain and update the website design. It provides powerful tools for controlling the appearance of web pages and offers a wide range of styling options to create visually appealing web pages.

2. ### Advantages of CSS:
    CSS provides several advantages, including:

    i. Separation of presentation and content: CSS allows you to separate the visual style of your website from the HTML content, making it easier to maintain and modify.
    ii. Consistency: By defining styles in one central CSS file, you can ensure that all pages on your website have a consistent look and feel.
    iii. Flexibility: CSS offers a wide range of styling options, including layout, color, font, and animation, giving you greater control over the appearance of your website.
    iv. Accessibility: With CSS, you can make your website more accessible to users with disabilities by using CSS to define font sizes, colors, and other elements that can be adjusted to meet their needs.

3. ### Syntax of CSS:
    The syntax of CSS is fairly simple and consists of two main parts: selectors and declarations.

    Selectors identify the HTML elements that you want to style, and declarations define the style properties that you want to apply to those elements.

    The basic syntax of CSS is:

    ```
    selector {
    property: value;
    property: value;
    }
    ```

4. ### Ways to include CSS in HTML file:
    There are three ways to insert CSS into an HTML document:

    i. Inline CSS: This involves adding the style attribute directly to an HTML element and defining the CSS rules within the attribute.

    ii. Internal CSS: This involves defining CSS rules within the head section of an HTML document, using the style element.

    iii. External CSS: This involves creating a separate CSS file and linking to it from your HTML document using the link element.

5. ### Diff between Inline, Internal, External CSS:
    Inline CSS is defined directly on an HTML element using the style attribute. Internal CSS is defined in the head section of an HTML document using the style element. External CSS is defined in a separate file and linked to the HTML document using the link element.

    The main differences between these three methods are:

    i. Inline CSS applies only to the element it is defined on, whereas internal and external CSS can apply to multiple elements.
    ii. Inline CSS can make the HTML code harder to read and maintain, whereas external CSS keeps the style information separate from the HTML content.
    iii. External CSS can be cached by the browser, which can improve the performance of your website.

6. ### comments in CSS:
    In CSS, you can add comments using the /* ... / syntax. Anything between the opening / and closing */ symbols is treated as a comment and ignored by the browser. For example:

        ```
        /* This is a CSS comment */
        ```

7. ### selectors in CSS:
    There are several basic selectors in CSS, including:

    i. Element selector: Selects elements based on their HTML tag name. For example: p { color: red; }
    ii. Class selector: Selects elements based on their class attribute. For example: .my-class { color: blue; }
    iii. ID selector: Selects elements based on their ID attribute. For example: #my-id { color: green; }
    iv. Universal selector: Selects all elements on a page. For example: * { font-size: 14px; }
    v. Attribute selector: Selects elements based on their attributes. For example: a[target="_blank"] { color: pink; }

8. ### descendant selectors:
    Descendant selectors are used to select elements that are descendants of another element. They are denoted by a space between two selectors. For example:
    ```
    ul li {
    color: red;
    }
    ```
    This selector selects all li elements that are descendants of a ul element.

9. ### child selectors:
    Child selectors in CSS are used to select and apply styles to elements that are direct children of a parent element. The child selector is denoted by the ">" symbol and is used in the following syntax:

    ```
    parent > child {
    /* CSS styles here */
    }
    ```
    In this syntax, "parent" refers to the parent element and "child" refers to the direct child element of the parent. By using the child selector, you can apply styles to specific child elements while ignoring any other descendants of the parent element.

    For example, the following code will select all li elements that are direct children of the ul element and apply a background color to them:

    ```
    ul > li {
    background-color: yellow;
    }
    ```
    This will only affect the direct child li elements of the ul element and not any other nested li elements within them.

10. ### adjacent selectors
    Adjacent selectors in CSS are used to select an element that immediately follows another element in the HTML document. The adjacent selector is represented by the plus symbol (+) and is used to select the next element that immediately follows the first one.

    For example, the following CSS code selects any p element that immediately follows a div element:

    ```
    div + p {
    /* CSS styles */
    }
    ```
    In this case, only p elements that come immediately after a div element will be selected and styled. The adjacent selector is useful when you want to apply a specific style to a specific element that comes immediately after another element.

