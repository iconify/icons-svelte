<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tajt5acui"/><path class="kqx16ebsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-report-problem" {...props}></Icon>
<style>
:global(.kqx16ebsu) {
  fill: currentColor;
  d: path("M12 2L1 21h22zm0 3.99L19.53 19H4.47zM11 16h2v2h-2zm0-6h2v4h-2z");
}

:global(.tajt5acui) {
  fill: currentColor;
  d: path("M12 5.99L4.47 19h15.06zM13 18h-2v-2h2zm-2-4v-4h2v4z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
