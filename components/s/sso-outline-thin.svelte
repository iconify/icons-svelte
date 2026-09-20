<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hvxngl_cs"/><path class="bfl7ipbld"/><path class="e1-kupvjo"/><path class="b0jxq8rov"/><path class="fiap06mao"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:sso-outline-thin" {...props}></Icon>
<style>
:global(.b0jxq8rov) {
  d: path("M15 4a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.bfl7ipbld) {
  d: path("M8 12h4V6h3");
}

:global(.e1-kupvjo) {
  d: path("M12 12v6h3");
}

:global(.fiap06mao) {
  d: path("M15 16a2 2 0 0 1 2 -2h3a2 2 0 0 1 2 2v4a2 2 0 0 1 -2 2h-3a2 2 0 0 1 -2 -2Z");
}

:global(.hntgybcog) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.hvxngl_cs) {
  d: path("M2 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

</style>
