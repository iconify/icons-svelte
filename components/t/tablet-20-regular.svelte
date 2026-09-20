<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cw6vesbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:tablet-20-regular" {...props}></Icon>
<style>
:global(.cw6vesbso) {
  fill: currentColor;
  d: path("M8.5 12a.5.5 0 0 0 0 1h3a.5.5 0 0 0 0-1zM4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zM3 6a1 1 0 0 1 1-1h12a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1z");
}

</style>
