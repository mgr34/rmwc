# Linear Progress

> Progress and activity indicators are visual indications of an app loading content.

- Module **@rmwc/linear-progress**
- Import styles:
  - Using CSS Loader
    - import **'@rmwc/linear-progress/styles';**
  - Or include stylesheets
    - **'@material/linear-progress/dist/mdc.linear-progress.css'**;
- MDC Docs: [https://material.io/develop/web/components/linear-progress/](https://material.io/develop/web/components/linear-progress/)

Default

```js

<LinearProgress progress\={0.5} />


```

Buffered

```js

<LinearProgress progress\={0.6} buffer\={0.8} />


```

Indeterminate

```js
<LinearProgress />
```

Reversed

```js
<LinearProgress reversed />
```

## LinearProgress