<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rr5o8luwc"/><path class="ui72q6bza"/><path class="rpf5c_bpp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:ski-school" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rpf5c_bpp) {
  d: path("M16 17.25v2.5q2 1.5 4 0v-2.5");
}

:global(.rr5o8luwc) {
  d: path("m3.5 19l13-13q1.25-1.25 2.75-1");
}

:global(.ui72q6bza) {
  d: path("M14.242 14.242L6 6Q4.75 4.75 3.25 5M16.5 16l.829-.415a1.5 1.5 0 0 1 1.342 0L19.5 16a.839.839 0 0 1 0 1.5l-.829.415a1.5 1.5 0 0 1-1.342 0L16.5 17.5a.839.839 0 0 1 0-1.5");
}

</style>
