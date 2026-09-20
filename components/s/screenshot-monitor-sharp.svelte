<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsge11b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:screenshot-monitor-sharp" {...props}></Icon>
<style>
:global(.qsge11b2v) {
  fill: currentColor;
  d: path("M15.5 15.692h3.192V12.5h-.884v2.308H15.5zM5.308 9.5h.884V7.192H8.5v-.884H5.308zM9 20v-2H3V4h18v14h-6v2z");
}

</style>
