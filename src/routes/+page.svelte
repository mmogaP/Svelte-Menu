<script>
	import Card from "$lib/Card.svelte";
</script>

<section >
    <Card/>
    
    <Card/>
    
    <Card/>
</section>

<style lang="postcss" scoped>
    section {
        @apply flex flex-row flex-wrap justify-center items-center gap-4;
    }
</style>
