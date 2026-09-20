<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hgajco8co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:view-headline-outline-sharp" {...props}></Icon>
<style>
:global(.hgajco8co) {
  fill: currentColor;
  d: path("M4 15v-2h16v2zm0 4v-2h16v2zm0-8V9h16v2zm0-4V5h16v2z");
}

</style>
