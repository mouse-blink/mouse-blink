<script lang="ts">
	import ArticlesBox from '$lib/components/Articles.svelte';
	export let data;
	const articles = data.articles;
</script>

<ArticlesBox {articles} />
