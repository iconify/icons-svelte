<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="hcr6wbqcp"/><path class="qck0jjbxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:trailforks" {...props}></Icon>
<style>
:global(.hcr6wbqcp) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 7.979L5.5 40.022h37zM24 26.5V17");
}

:global(.qck0jjbxf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29 36.887v-7L24 26.5l-5 3.387v7");
}

</style>
