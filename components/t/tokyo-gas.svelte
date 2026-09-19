<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k42l4pbta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tokyo-gas" {...props}></Icon>
<style>
:global(.k42l4pbta) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.833 17.833H5.5V5.5h37v12.333H30.167V42.5H42.5V30.167H17.833z");
}

</style>
