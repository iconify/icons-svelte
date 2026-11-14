<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="voincubod"/><path class="des5jubpl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:timelapse" {...props}></Icon>
<style>
:global(.des5jubpl) {
  d: path("m4.25 3l3 .75l-.75 3M12 7v5l3.5 2");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.voincubod) {
  d: path("M12 2.5a9.5 9.5 0 1 1-4.75 1.25");
}

</style>
