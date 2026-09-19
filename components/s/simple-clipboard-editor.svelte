<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="od6ziru9m"/><circle class="xazr_i00f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:simple-clipboard-editor" {...props}></Icon>
<style>
:global(.od6ziru9m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.857 15.136h20.286m-6.091-6.584a4.052 4.052 0 0 0-8.104 0H9.298V43.5h29.403V8.552z");
}

:global(.xazr_i00f) {
  cx: 24px;
  cy: 8.552px;
  r: 0.75px;
  fill: currentColor;
}

</style>
