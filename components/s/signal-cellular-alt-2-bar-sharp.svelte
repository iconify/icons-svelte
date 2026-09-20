<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xla7kib8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-alt-2-bar-sharp" {...props}></Icon>
<style>
:global(.xla7kib8f) {
  fill: currentColor;
  d: path("M5 20v-6h3v6zm6 0V9h3v11z");
}

</style>
