<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bhd8q83uz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:signal-cellular-pause-sharp" {...props}></Icon>
<style>
:global(.bhd8q83uz) {
  fill: currentColor;
  d: path("M3 21L21 3v10.73h-6.884V21zm16.5 0v-4.884h1V21zm-3 0v-4.884h1V21z");
}

</style>
