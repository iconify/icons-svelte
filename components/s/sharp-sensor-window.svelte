<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ox8nwiisu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-sensor-window" {...props}></Icon>
<style>
:global(.ox8nwiisu) {
  fill: currentColor;
  d: path("M18 4v16H6V4zM4 2v20h16V2zm3 17h10v-6H7zm3-9h4v1h3V5H7v6h3z");
}

</style>
