<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b32f57vse"/><path class="oa-2fvpyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-bungalow" {...props}></Icon>
<style>
:global(.b32f57vse) {
  fill: currentColor;
  d: path("m12 6.78l-3 4.8V19h2v-3h2v3h2v-7.42zM13 14h-2v-2h2z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

:global(.oa-2fvpyx) {
  fill: currentColor;
  d: path("M13 14h-2v-2h2zm5.1 2.56L17 14.79V21H7v-6.2l-1.1 1.76l-1.7-1.06L12 3l7.8 12.5zM15 11.59l-3-4.8l-3 4.8V19h2v-3h2v3h2z");
}

</style>
