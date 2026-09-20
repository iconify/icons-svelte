<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6-ct6bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shades-sharp" {...props}></Icon>
<style>
:global(.d6-ct6bdy) {
  fill: currentColor;
  d: path("M3 22V4H2V2h20v2h-1v18q-2.35 0-4.212-1.375T14.275 17H9.7q-.675 2.25-2.525 3.625T3 22m7-7h4V4h-4z");
}

</style>
