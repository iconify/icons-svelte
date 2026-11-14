<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8w4dv7wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:underground-depth" {...props}></Icon>
<style>
:global(.g8w4dv7wc) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 7h19m-6-4v17.5M12 17l3.5 3.5L19 17M6 7v13.5m0-6.75h3M6 20.5h3");
}

</style>
