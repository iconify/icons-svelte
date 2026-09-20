<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="k0g0vebmi"/><path class="v_99wwbie"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:smartphone-home-button" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.k0g0vebmi) {
  fill-rule: evenodd;
  d: path("M14.5 0h-9a2 2 0 0 0-2 2v16a2 2 0 0 0 2 2h9a2 2 0 0 0 2-2V2a2 2 0 0 0-2-2m-9 18V2h9v16z");
}

:global(.v_99wwbie) {
  d: path("M10 17.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5");
}

</style>
