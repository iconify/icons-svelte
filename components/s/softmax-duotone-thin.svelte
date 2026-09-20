<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hsnj9o-9y"/><path class="puskh763k"/><path class="b577pibsg"/><path class="jzwk6ubza"/><path class="sh-bzloxt"/><path class="jkuojibnm"/><path class="d1du4rxru"/><path class="a9cczt5un"/><path class="t3w_facee"/><path class="j4if4rbfv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:softmax-duotone-thin" {...props}></Icon>
<style>
:global(.a9cczt5un) {
  d: path("M10 8v12");
}

:global(.b577pibsg) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M10 8v12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.d1du4rxru) {
  d: path("M6 14v6");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hsnj9o-9y) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.j4if4rbfv) {
  d: path("M18 14v6");
}

:global(.jkuojibnm) {
  d: path("M3 20h18");
}

:global(.jzwk6ubza) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14 3v17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.puskh763k) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.sh-bzloxt) {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M18 14v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.t3w_facee) {
  d: path("M14 3v17");
}

</style>
