<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gr2theeis"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:switch-left" {...props}></Icon>
<style>
:global(.gr2theeis) {
  fill: currentColor;
  d: path("m10 19l-7-7l7-7zm-1.5-3.625v-6.75L5.125 12zM14 19V5l7 7z");
}

</style>
