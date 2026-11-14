<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_wymbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:storm-shelter" {...props}></Icon>
<style>
:global(.fz_wymbcz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 18L7.5 7h9L19 18M2.5 18h19M12 7v11m-2.75-5.5h.01m5.49 0h.01");
}

</style>
