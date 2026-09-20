<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re8qaebdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:subject" {...props}></Icon>
<style>
:global(.re8qaebdw) {
  fill: currentColor;
  d: path("M4 19v-2h10v2zm0-4v-2h16v2zm0-4V9h16v2zm0-4V5h16v2z");
}

</style>
