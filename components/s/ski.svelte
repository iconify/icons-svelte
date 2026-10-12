<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e8p60ibls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:ski" {...props}></Icon>
<style>
:global(.e8p60ibls) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21.25V6.5a3.75 3.75 0 0 1 3.75-3.75M10 21.25V6.5a3.75 3.75 0 0 1 3.75-3.75M16 4.5v16.75M20 4.5v16.75m-5.25-3.5h2.5m1.5 0h2.5");
}

</style>
