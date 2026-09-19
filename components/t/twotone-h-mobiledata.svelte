<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxkfhs9ju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-h-mobiledata" {...props}></Icon>
<style>
:global(.yxkfhs9ju) {
  fill: currentColor;
  d: path("M15 11H9V7H7v10h2v-4h6v4h2V7h-2z");
}

</style>
