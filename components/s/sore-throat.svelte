<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ese90xnzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:sore-throat" {...props}></Icon>
<style>
:global(.ese90xnzd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.75 21.25v-6h1.5A1.25 1.25 0 0 0 17.5 14v-1.75l1.25-.5c.45-.2.55-.6.3-1l-1.05-2c-.25-3.5-2.75-6-6.5-6c-4 0-6.75 2.75-6.75 6.5c0 2.25.9 4 2.25 5.25v6.75Zm3-4l2.5-.75m-2.5 4l2.5.75");
}

</style>
