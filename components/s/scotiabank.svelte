<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="c6j4q5bhh"/><circle class="f7wqasbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:scotiabank" {...props}></Icon>
<style>
:global(.c6j4q5bhh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m34.5 12l6.749-7.5h-19.5c-9 0-15 11.25-9.75 18C12 18 18 12 21 12zm-21 24l-6.749 7.5H26.25c9 0 14.999-11.25 9.75-18C36 30 30 36 27 36z");
}

:global(.f7wqasbkf) {
  cx: 24px;
  cy: 24px;
  r: 9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
