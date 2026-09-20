<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v5furukpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:variable-remove-outline-sharp" {...props}></Icon>
<style>
:global(.v5furukpz) {
  fill: currentColor;
  d: path("M14.058 16H4V8h16v2.058h-1V9H5v6h9.058zM5 15V9zm11.442 2.389l2.12-2.12l-2.12-2.119l.708-.708l2.12 2.12l2.119-2.12l.707.708l-2.113 2.12l2.113 2.119l-.707.707l-2.12-2.113l-2.119 2.113z");
}

</style>
