<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vmflwbtqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tachometer" {...props}></Icon>
<style>
:global(.vmflwbtqr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 39.203a21.5 21.5 0 1 1 30.406 0M24 24L11.393 11.393");
}

</style>
