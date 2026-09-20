<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="li_ylqjgz"/><path class="smxtbacxz"/><path class="wubtydbvb"/><path class="u85q0ssbo"/><path class="jnf_2db5t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconmind:unplug-duotone-regular" {...props}></Icon>
<style>
:global(.jnf_2db5t) {
  d: path("M12 18v3");
}

:global(.li_ylqjgz) {
  fill: currentColor;
  d: path("M6 7h12v5l-6 6 -6 -6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

:global(.nrj6p8qat) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

:global(.smxtbacxz) {
  d: path("M9 3v4");
}

:global(.u85q0ssbo) {
  d: path("M6 7h12v5l-6 6 -6 -6Z");
}

:global(.wubtydbvb) {
  d: path("M15 3v4");
}

</style>
