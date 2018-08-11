# sw4p-tool
A Polymer Web Component written for [sw4pspace.com](https://sw4psapce.com) to display tools

## Example
```html
<sw4p-tool href="/">
    <span slot="title">JSON Editor</span>
    <span slot="description">Edit and Minify JSON</span>
    <div slot="actions">
        <button>Open</button>
        <button>Source Code</button>
    </div>
</sw4p-tool>
```

## Demo
Run `polymer serve` from root directory.  
Open http://127.0.0.1:8001/components/sw4p-tool/demo/ in your browser.
