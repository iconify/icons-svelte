<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lhhe59byw"/><path class="f-5eluf_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:true-gigatex" {...props}></Icon>
<style>
:global(.f-5eluf_g) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.696 19.129L24 7.132l17.73 33.734h-6.305L24 19.13h0z");
}

:global(.lhhe59byw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.363 22.244l-9.788 18.623H6.271l9.788-18.624z");
}

</style>
