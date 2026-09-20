<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uz43wjbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tab-outline-sharp" {...props}></Icon>
<style>
:global(.uz43wjbwe) {
  fill: currentColor;
  d: path("M4 18h16v-8h-7V6H4zm-1 1V5h18v14zm1-1V6z");
}

</style>
