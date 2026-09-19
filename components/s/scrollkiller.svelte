<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ij3d2-bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:scrollkiller" {...props}></Icon>
<style>
:global(.ij3d2-bhd) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.422 4.5v39h23.156v-39zm0 0l23.156 39m-23.156 0l23.156-39");
}

</style>
