<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="qu-s1dbay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:transports-publics-genevois" {...props}></Icon>
<style>
:global(.qu-s1dbay) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.125 11.375h5.75C33.848 11.375 39.5 17.027 39.5 24s-5.652 12.625-12.625 12.625h-5.75C14.152 36.625 8.5 30.973 8.5 24s5.652-12.625 12.625-12.625m5.75 0H43.5m-22.375 25.25H4.5");
}

</style>
