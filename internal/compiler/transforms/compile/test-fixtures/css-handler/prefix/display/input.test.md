# `index.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/transforms/compile/index.test.ts --update-snapshots` to update.

## `css-handler > prefix > display`

### `Diagnostics`

```

```

### `Input`

```css
.style {
	text-align: center;
	display: flex;
	align-content: center;
}

.style {
	display: flex;
}

.style {
	text-align: center;
	display: flex;
	display: -webkit-flex;
	align-content: center;
}

.style {
	text-align: center;
	display: inline flex;
	align-content: center;
}

.style {
	text-align: center;
	display: inline-flex;
	align-content: center;
}

.style {
	text-align: center;
	display: inline-flex;
	display: -webkit-inline-flex;
	align-content: center;
}

```

### `Output`

```css
.style {
	text-align: center;
	display: -moz-box;
	display: -webkit-flex;
	display: flex;
	align-content: center;
}

.style {
	display: -moz-box;
	display: -webkit-flex;
	display: flex;
}

.style {
	text-align: center;
	display: -moz-box;
	display: flex;
	display: -webkit-flex;
	align-content: center;
}

.style {
	text-align: center;
	display: inline flex;
	align-content: center;
}

.style {
	text-align: center;
	display: -moz-inline-box;
	display: -webkit-inline-flex;
	display: inline-flex;
	align-content: center;
}

.style {
	text-align: center;
	display: -moz-inline-box;
	display: inline-flex;
	display: -webkit-inline-flex;
	align-content: center;
}

```
