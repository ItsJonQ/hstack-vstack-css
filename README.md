# 🗄 HStack and VStack in CSS

> CSS layout components that (basically) horizontally and vertically stack anything.

## Usage

✌️ Check out the **[code here](https://github.com/ItsJonQ/hstack-vstack-css/blob/master/src/styles.css)**.

### Horizontally Stacking

The `.spacer` is used in the (below) example to push the items apart.

```html
<div class="flex hstack">
	<div>🌭</div>
	<div>🍕</div>
	<div class="spacer"></div>
	<div>🍟</div>
</div>
```

### Vertically Stacking

```html
<div class="flex vstack">
	<div>🌭</div>
	<div>🍕</div>
	<div>🍟</div>
</div>
```

### Swapping from VStack to HStack (responsively)

The example below stacks items vertically on mobile. However, the items stack horizontally at the medium breakpoint for tablets.

```html
<div class="flex vstack hstack@md">
	<div>🌭</div>
	<div>🍕</div>
	<div>🍟</div>
</div>
```
