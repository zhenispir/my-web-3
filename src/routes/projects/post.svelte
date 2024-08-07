<script>
	export let title;
	export let date;
    export let category;
</script>

<article>
	<h1>{title}</h1>

	<p>Published: {date}</p>
    <p>Categories: {category}</p>

	<slot />
</article>

