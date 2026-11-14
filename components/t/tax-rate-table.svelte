<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zdf4r7v7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tax-rate-table" {...props}></Icon>
<style>
:global(.zdf4r7v7t) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.6 18.5H2.5v-16h18v9.1m-18-4.1h18m-18 5h17.1M9.5 2.5v16m5.25 2.75l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
