<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jbtpagb-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:sailing-trip" {...props}></Icon>
<style>
:global(.jbtpagb-s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5V16H5.5Zm0 3l6.5 9.5H12m-8.5 3h17l-2 2h-13Z");
}

</style>
