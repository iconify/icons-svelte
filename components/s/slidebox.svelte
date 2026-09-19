<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="amhwl3acz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:slidebox" {...props}></Icon>
<style>
:global(.amhwl3acz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.586 6.086l-16.5 16.5a2 2 0 0 0 0 2.828l16.5 16.5a2 2 0 0 0 2.828 0l16.5-16.5a2 2 0 0 0 0-2.828l-16.5-16.5a2 2 0 0 0-2.828 0");
}

</style>
