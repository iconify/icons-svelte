<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dt_kzxb6g"/><path class="bpny-o4rm"/><path class="rjyplsjao"/><path class="yzgz32bhq"/><path class="cwatz7g8l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-cross-line-duotone" {...props}></Icon>
<style>
:global(.bpny-o4rm) {
  d: path("M5.33301 12.295C7.42965 10.032 10.2681 9.05764 13.0035 9.37195");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.cwatz7g8l) {
  d: path("M22 5.00002L19 8.00001M19 8.00001L16 11M19 8.00001L16 5M19 8.00001L21.9999 11");
}

:global(.dt_kzxb6g) {
  d: path("M8.66699 15.8931C10.5079 13.9061 13.4927 13.9061 15.3337 15.8931");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.ipq1z-bjh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

:global(.rjyplsjao) {
  d: path("M2 8.69694C5.01816 5.43925 9.06111 3.96185 13.0088 4.26472");
  opacity: var(--svg-opacity--0-5, 0.5);
}

:global(.yzgz32bhq) {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
