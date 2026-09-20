<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jyikixfvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:unfloat-landscape-outline-sharp" {...props}></Icon>
<style>
:global(.jyikixfvw) {
  fill: currentColor;
  d: path("M2 20V4h20v7h-2V6H4v12h11v2Zm9.075-5.5l1.425-1.425L9.4 10H12V8H6v6h2v-2.575ZM17 20v-7h5v7Zm-5-8Z");
}

</style>
