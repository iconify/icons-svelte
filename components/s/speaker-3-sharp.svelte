<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3c8e8bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:speaker-3-sharp" {...props}></Icon>
<style>
:global(.e3c8e8bau) {
  fill: currentColor;
  d: path("M8 22v-1H4V2h16v19h-4v1z");
}

</style>
