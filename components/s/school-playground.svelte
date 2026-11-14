<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fztekhcov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:school-playground" {...props}></Icon>
<style>
:global(.fztekhcov) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 21V7m4 14V7m-4 4.5h4M4 16h4m0-9c2 0 3 1 4 3l4 8c.75 1.5 2 2.5 4 2.5");
}

</style>
