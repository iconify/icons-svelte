<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ltcmuob9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:severity-major" {...props}></Icon>
<style>
:global(.ltcmuob9s) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.023 18.5H2.5L11 3l5.323 9.167M11 9.25v3m0 3h.01M15.5 17l2.75-2.75L21 17m-5.5 4l2.75-2.75L21 21");
}

</style>
