<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu06o3beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:test-plus" {...props}></Icon>
<style>
:global(.qu06o3beq) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 3.5v14a3 3 0 0 0 6 0v-14m-7.5 0h9M6 11h6m6 4v6m-3-3h6");
}

</style>
