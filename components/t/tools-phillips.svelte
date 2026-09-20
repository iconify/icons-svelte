<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6antbal"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:tools-phillips" {...props}></Icon>
<style>
:global(.lt6antbal) {
  fill: currentColor;
  d: path("M8 20v-1h8v1zm0-2V9.327L11.25 5h1.5L16 9.327V18zm1-5.288l2.5-2.5V6.327L9 9.675zm6 0V9.675l-2.5-3.348v3.885z");
}

</style>
