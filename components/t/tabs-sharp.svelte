<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dpw0pqbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tabs-sharp" {...props}></Icon>
<style>
:global(.dpw0pqbzm) {
  fill: currentColor;
  d: path("M3 21V3h18v18zm2-2h14v-7H5zm7-11h6V6h-6z");
}

</style>
