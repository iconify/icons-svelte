<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2nqnuc_p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:unfloat-portrait-sharp" {...props}></Icon>
<style>
:global(.t2nqnuc_p) {
  fill: currentColor;
  d: path("m13.075 12.5l1.425-1.425L11.425 8H14V6H8v6h2V9.4ZM15 22v-7h5v7ZM4 22V2h16v11h-7v9Z");
}

</style>
