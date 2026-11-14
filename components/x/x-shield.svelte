<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u9oxoibvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:x-shield" {...props}></Icon>
<style>
:global(.u9oxoibvw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6ZM9.5 9l5 5m0-5l-5 5");
}

</style>
