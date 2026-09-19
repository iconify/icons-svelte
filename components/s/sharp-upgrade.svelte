<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i64c76btm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-upgrade" {...props}></Icon>
<style>
:global(.i64c76btm) {
  fill: currentColor;
  d: path("M16 18v2H8v-2zM11 7.99V16h2V7.99h3L12 4L8 7.99z");
}

</style>
