<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-gyshbnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:single-arrow-outline-rounded" {...props}></Icon>
<style>
:global(.j-gyshbnk) {
  fill: currentColor;
  d: path("M12.775 12L8.9 6.575q-.35-.5-.088-1.037T9.7 5q.25 0 .475.113t.35.312l4.7 6.575l-4.7 6.575q-.125.2-.35.313T9.7 19q-.6 0-.875-.537t.075-1.038z");
}

</style>
