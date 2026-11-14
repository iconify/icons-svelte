<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="aihfrab2h"/><path class="dckcxggmq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:update-check" {...props}></Icon>
<style>
:global(.aihfrab2h) {
  d: path("M17.785 5.106a9 9 0 1 1-8.863-1.563");
}

:global(.dckcxggmq) {
  d: path("M5.75 3.5h3v3m-.75 6l3 3l5-6");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
