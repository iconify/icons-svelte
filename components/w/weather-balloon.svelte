<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r25n_jokt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:weather-balloon" {...props}></Icon>
<style>
:global(.r25n_jokt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.5C8 13 5.5 11 5.5 8.5c0-3.5 3-6 6.5-6s6.5 2.5 6.5 6c0 2.5-2.5 4.5-6.5 7ZM9.5 18h5v3.5h-5Zm2.5-2.5V18");
}

</style>
