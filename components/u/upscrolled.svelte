<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="x369gu3sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:upscrolled" {...props}></Icon>
<style>
:global(.x369gu3sl) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.445 6v10.688c0 5.289 3.847 9.67 8.894 10.526V14.905H28.82a9.8 9.8 0 0 1 2 .207V6zm21.375 9.112v1.575c0 5.903-4.785 10.688-10.687 10.688c-.613 0-1.21-.062-1.794-.161V42l6.13-7.628h4.352c5.376 0 9.734-4.358 9.734-9.733c0-4.69-3.318-8.605-7.735-9.527");
}

</style>
