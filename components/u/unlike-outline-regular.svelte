<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkje5bbsk"/><path class="fk8qv-tpl"/><path class="c3lntibww"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unlike-outline-regular" {...props}></Icon>
<style>
:global(.c3lntibww) {
  d: path("m22 9 -7 7");
}

:global(.fk8qv-tpl) {
  d: path("m15 9 7 7");
}

:global(.lkje5bbsk) {
  d: path("M2 9a2.5 2.5 0 0 1 5 0 2.5 2.5 0 0 1 5 0l-5 5Z");
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
