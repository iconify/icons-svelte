<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fmu4-itzh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-stream-sharp" {...props}></Icon>
<style>
:global(.fmu4-itzh) {
  fill: currentColor;
  d: path("M4 18v-5.5h16V18zm0-6.5V6h16v5.5z");
}

</style>
