<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq4wcu2jz"/><circle class="u1l7rqbek"/><path class="tv5w3ab-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-category" {...props}></Icon>
<style>
:global(.tv5w3ab-g) {
  fill: currentColor;
  d: path("M3 13.5h8v8H3z");
}

:global(.u1l7rqbek) {
  cx: 17.5px;
  cy: 17.5px;
  r: 4.5px;
  fill: currentColor;
}

:global(.vq4wcu2jz) {
  fill: currentColor;
  d: path("m12 2l-5.5 9h11z");
}

</style>
