<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3tca8coq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:trigger-outline-regular" {...props}></Icon>
<style>
:global(.x3tca8coq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m16 4 -7 7h5l-7 7");
}

</style>
