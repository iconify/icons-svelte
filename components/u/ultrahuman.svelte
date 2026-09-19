<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d-3ijac4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:ultrahuman" {...props}></Icon>
<style>
:global(.d-3ijac4j) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 29.804l-9.583-8.89h6.238V9.594H7.845v11.32h6.565L4.5 30.107l7.699 8.299l11.964-11.099l11.638 10.796z");
}

</style>
