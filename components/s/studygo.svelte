<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="pkzftpb3k"/><path class="bt1m4ibra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:studygo" {...props}></Icon>
<style>
:global(.bt1m4ibra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.188 27.119l11.041-2.027l2.027 11.041");
}

:global(.pkzftpb3k) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.642 15.54C35.492 9.007 30.832 4.5 23.094 4.5c-10.769 0-17.35 8.73-17.35 19.5s6.58 19.5 17.35 19.5c12.628 0 16.64-10.042 17.135-18.408");
}

</style>
