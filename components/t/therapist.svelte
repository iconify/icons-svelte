<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jhnjf9l3r"/><path class="rkgv-rmmm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:therapist" {...props}></Icon>
<style>
:global(.jhnjf9l3r) {
  d: path("M11.734 21H3.5c-.6 0-1-.4-1-1c0-2.75 2.9-4.75 6.5-4.75c.973 0 1.895.146 2.722.413M5.25 8.25a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm9.25 6.25h7V22h-7Z");
}

:global(.rkgv-rmmm) {
  d: path("M16.5 13.5h3v2h-3Zm.25 5.25h2.5");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
