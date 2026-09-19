<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="s9fkwsglj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:zelle" {...props}></Icon>
<style>
:global(.s9fkwsglj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.531 12.22H35.47L12.53 35.78h22.94m-11.47 0v7.72m0-39v7.72");
}

</style>
