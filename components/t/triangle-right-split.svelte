<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qow38acpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangle-right-split" {...props}></Icon>
<style>
:global(.qow38acpc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.089 20.153C20.651 19.608 21 18.845 21 18V4.503C21 3.167 19.384 2.497 18.439 3.442L10.941 10.941L3.442 18.439C2.497 19.384 3.167 21 4.503 21H18C18.812 21 19.549 20.677 20.089 20.153ZM10.941 10.941L20.089 20.153");
}

</style>
