<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p91o0plsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:service-helpdesk" {...props}></Icon>
<style>
:global(.p91o0plsj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14h19m-17 0v7m15-7v7M7 14a5 5 0 0 1 10 0m-5-7.5V9m-1.5-2.5h3");
}

</style>
