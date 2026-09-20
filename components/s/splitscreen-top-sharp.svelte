<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ft7496cia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:splitscreen-top-sharp" {...props}></Icon>
<style>
:global(.ft7496cia) {
  fill: currentColor;
  d: path("M4 10.616v-6h16v6zm0 8.769v-6h16v6zm1-1h14v-4H5z");
}

</style>
