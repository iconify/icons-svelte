<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="bml3n8lpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:youdao-note" {...props}></Icon>
<style>
:global(.bml3n8lpj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.82 42.241l19.522-19.884l-16.87-16.63L5.707 25.37l-.05 16.903Z");
}

</style>
