<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ix06gebmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vertical-shades" {...props}></Icon>
<style>
:global(.ix06gebmg) {
  fill: currentColor;
  d: path("M2 21v-2h2V3h16v16h2v2zm8-2h4V5h-4z");
}

</style>
