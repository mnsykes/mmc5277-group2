# Colors

    Primary red: #a41d17;
    Primary black: #0f0f27;
    Primary white: #f1f2f2;
    Accent green: #03300b;
    Accent orange: #db512d;
    Accent red: #e12712;

# Fonts

- BenguitStd-Book
- BenguitStd-Medium
- BenguitStd-Bold

# Typography

# Heading 1, 4.8rem

## Heading 2, 3rem

### Heading 3, 2.4rem

#### Heading 4, 1.8rem

##### Heading 5, 1.5rem

###### Heading 6, 1rem

# CSS Rules

We will be using rem units rather than pixels for sizing. The base unit is set at 10px to make conversions easy.
With this setup, 1rem = 10px.

# HTML Rules

- Indent nested HTML tags

Use comments for long code or descriptive sections. Minimize code between comments to make readability and finding code easier.

```html
<!-- THIS COMMENT STARTS A CODE BLOCK -->
<div class="block">
	<div class="some-content"></div>
	<div class="some-other-content"></div>
</div>
<!-- THIS COMMENT ENDS A CODE BLOCK -->
```

```html
<!-- START MAIN -->
<main class="main__wrapper">
	<h1 class="heading">Nerds, Do You Copy?</h1>
	<h2 class="subheading">Stranger Things 4 is Now Streaming!</h2>
	<!-- START HERO -->
	<section class="hero">
		<div class="hero__jumbotron hero__jumbotron_home">
			<h2 class="subheading">Every ending has a beginning.</h2>
			<button class="btn btn_primary">Watch Now</button>
		</div>
	</section>
	<!-- END HERO -->

	<!-- START CONTENT -->
	<section class="content">
		<h2 class="subheading">Return to the Upside Down</h2>
		<article class="content__article">
			<p class="body-text">
				Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde illum, magni, odio quas
				commodi iste accusantium porro ea optio quo nobis consequuntur molestias quaerat in sunt
				recusandae quisquam deleniti illo dignissimos cum. Totam eum error vitae temporibus ipsum
				eaque voluptatibus!
			</p>
		</article>
	</section>
	<!-- END CONTENT -->
</main>
<!-- END MAIN -->
```

```html
<body>
	<!-- START HEADER -->
	<header class="header"></header>
	<!-- END HEADER -->

	<!-- START MAIN -->
	<main class="main__wrapper"></main>
	<!-- END MAIN -->

	<!-- START FOOTER -->
	<footer class="footer"></footer>
	<!-- END FOOTER -->
</body>
```
