<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ae0aziysf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:table-add-column" {...props}></Icon>
<style>
:global(.ae0aziysf) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 4H9a3.5 3.5 0 0 1 3.5 3.5v9A3.5 3.5 0 0 1 9 20H6.5A3.5 3.5 0 0 1 3 16.5v-9A3.5 3.5 0 0 1 6.5 4m1.25 0v16M18.5 9v6m-3-3h6");
}

</style>
