<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n4-agze3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:wall-lamp-sharp" {...props}></Icon>
<style>
:global(.n4-agze3v) {
  fill: currentColor;
  d: path("M3 21v-6h2v6zm3-2v-2h6v-4H5.65l3-10h8.7l3 10H14v6z");
}

</style>
