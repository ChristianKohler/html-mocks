# html-mocks
HTML Mocks Web Components

A collection of web components for mocking

## Usage

Install via npm

    npm install html-mocks

Include the `dist/prism-components.html` file in your project.

    <link rel="import" href="html-mocks.html">

### Mockup Window

```html
<mockup-window></mockup-window>
```
### Mockup Browser

```html
<mockup-browser></mockup-browser>
```

## Style Mockups

```css
mockup-browser {
    width: 20px;
    box-shadow: 0px 0px 3px 3px rgba(70, 70, 70, 0.2);
}
```

## Requirements
Use Chrome 36 or higher to use web-presentation without a polyfill.

## Notes
Don't use this components in a public website since it works only on Chrome 36 or higher. On a browser without web components support, the user still sees the code but without highlighting.
