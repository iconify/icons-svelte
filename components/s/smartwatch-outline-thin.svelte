<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s5rwf4b1t"/><path class="jms1xqp8l"/><path class="wtnr1t2-w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:smartwatch-outline-thin" {...props}></Icon>
<style>
:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.jms1xqp8l) {
  d: path("M9 3h6");
}

:global(.s5rwf4b1t) {
  d: path("M7 8a2 2 0 0 1 2 -2h6a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H9a2 2 0 0 1 -2 -2Z");
}

:global(.wtnr1t2-w) {
  d: path("M9 21h6");
}

</style>
