# Notes Regarding The Development Process

## Configuring TailwindCSS

- Official Link: [Tailwind Website](https://tailwindcss.com/docs/installation/framework-guides/angular)

## Creating Header Component

```bash
ng g c components/header
```

- Can be called as a web component based on the selector name.

- Make sure to include it in the imports sections of the page.

### Emmet Tips

- This Emmet Snippet:

```
div>div>div>h1{eStore}
```

- Produces this:

```html
<div>
  <div>
    <div>
      <h1>eStore</h1>
    </div>
  </div>
</div>
```
