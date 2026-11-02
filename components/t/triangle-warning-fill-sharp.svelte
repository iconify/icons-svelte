<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz6kgrblf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:triangle-warning-fill-sharp" {...props}></Icon>
<style>
:global(.pz6kgrblf) {
  fill: currentColor;
  d: path("m12.874 1.514l10 18A1 1 0 0 1 22 21H2a1 1 0 0 1-.874-1.486l10-18a1 1 0 0 1 1.748 0M13 9a1 1 0 0 0-2 0v4a1 1 0 0 0 2 0Zm-1 6a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Z");
}

</style>
