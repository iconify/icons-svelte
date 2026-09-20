<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="oyefdmbym"/><path class="nl-1o5faa"/><path class="gy66xabxx"/><path class="l9c3qzbax"/><path class="e99hiubds"/><path class="h3aib2b4u"/><path class="qsabb4b5g"/><path class="dihddo_by"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:swing-duotone-bold" {...props}></Icon>
<style>
:global(.dihddo_by) {
  d: path("M6 18h12");
}

:global(.e99hiubds) {
  d: path("M5 3h14");
}

:global(.gy66xabxx) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M16 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.h3aib2b4u) {
  d: path("M8 3v15");
}

:global(.l9c3qzbax) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 18h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.nl-1o5faa) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 3v15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.oyefdmbym) {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M5 3h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

:global(.qsabb4b5g) {
  d: path("M16 3v15");
}

:global(.s0phu2bbs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
