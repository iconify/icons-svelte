<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj7rrhbiw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:spring-stretched" {...props}></Icon>
<style>
:global(.wj7rrhbiw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V5l5 2l-10 3l10 3l-10 3l5 2v3.5m-3-19h6m-6 19h6");
}

</style>
