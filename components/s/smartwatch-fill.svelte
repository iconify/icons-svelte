<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slclfpbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:smartwatch-fill" {...props}></Icon>
<style>
:global(.slclfpbyv) {
  fill: currentColor;
  d: path("M16 5a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3a3 3 0 0 1-3-3V8a3 3 0 0 1 3-3a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3m-2 0a.997.997 0 0 0-1-1h-2a.997.997 0 0 0-1 1Zm-3 15h2a1 1 0 0 0 1-1h-4a1 1 0 0 0 1 1");
}

</style>
