<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="t2qp5xb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:topmixtapes" {...props}></Icon>
<style>
:global(.t2qp5xb4x) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.51 12.225v25.664m7.949-18.555v11.473M24.137 5.5v37M13.9 5.5h20.475m-18.556 9.113v20.805M7.541 19.361v11.282");
}

</style>
