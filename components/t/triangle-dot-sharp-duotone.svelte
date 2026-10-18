<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lxy-_jbnf"/><path class="q7lztj58y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangle-dot-sharp-duotone" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.lxy-_jbnf) {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.1258 2.5144C11.5068 1.8285 12.4932 1.8285 12.8742 2.5144L22.8742 20.5144C23.2445 21.1809 22.7625 22 22 22L2 22C1.2375 22 0.7555 21.1809 1.1258 20.5144L11.1258 2.5144Z");
}

:global(.q7lztj58y) {
  d: path("M14 14C14 15.1046 13.1046 16 12 16C10.8954 16 10 15.1046 10 14C10 12.8954 10.8954 12 12 12C13.1046 12 14 12.8954 14 14Z");
}

</style>
