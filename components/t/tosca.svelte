<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vzubpablo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tosca" {...props}></Icon>
<style>
:global(.vzubpablo) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m8 17.5l32-13m-32 39l32-13m-32 0l32-13m-13.854-13H8m32 39H21.854");
}

</style>
