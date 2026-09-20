<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ttzw2gbcj"/><path clip-rule="evenodd" class="d7hkwttlg"/><path class="ru-d6_b-z"/><path clip-rule="evenodd" class="mu2p0mb8a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:smartphone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.d7hkwttlg) {
  fill-rule: evenodd;
  d: path("M14.5 0h-9c-1.105 0-2 .943-2 2.105v15.79c0 1.162.895 2.105 2 2.105h9c1.105 0 2-.943 2-2.105V2.105C16.5.943 15.605 0 14.5 0Zm-9 18V2h9v16h-9Z");
}

:global(.mu2p0mb8a) {
  fill-rule: evenodd;
  d: path("M9 16.5a1 1 0 1 1 2 0a1 1 0 0 1-2 0Z");
}

:global(.ru-d6_b-z) {
  d: path("M10.5 16.5a.5.5 0 1 1-1 0a.5.5 0 0 1 1 0Z");
}

:global(.ttzw2gbcj) {
  fill-rule: evenodd;
  d: path("M6.25 3a.25.25 0 0 1 .25-.25h7a.25.25 0 0 1 .25.25v12a.25.25 0 0 1-.25.25h-7a.25.25 0 0 1-.25-.25V3Z");
}

</style>
