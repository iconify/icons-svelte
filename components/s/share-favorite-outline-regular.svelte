<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lkje5bbsk"/><path class="eud-3ptuk"/><path class="owdk3hf1a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:share-favorite-outline-regular" {...props}></Icon>
<style>
:global(.eud-3ptuk) {
  d: path("M15 12h7");
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

:global(.owdk3hf1a) {
  d: path("m18 8 4 4 -4 4");
}

</style>
