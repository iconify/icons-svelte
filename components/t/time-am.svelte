<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1ore1bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:time-am" {...props}></Icon>
<style>
:global(.o1ore1bau) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.5L6 6.5l3.5 11M4 13h4m4 4.5v-11l4.25 6l4.25-6v11");
}

</style>
