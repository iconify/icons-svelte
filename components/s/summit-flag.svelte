<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfm-cdc0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:summit-flag" {...props}></Icon>
<style>
:global(.rfm-cdc0o) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 20.5l7.5-13l4 5.5l2.5-3l5 10.5Zm7.5-13v-5l5.5 2l-5.5 2");
}

</style>
