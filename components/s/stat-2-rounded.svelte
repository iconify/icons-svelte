<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj0uuig3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stat-2-rounded" {...props}></Icon>
<style>
:global(.wj0uuig3p) {
  fill: currentColor;
  d: path("m12 13.114l-4.246 4.24q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354l4.221-4.221q.306-.306.733-.306t.733.306l4.22 4.221q.141.14.154.342t-.153.366q-.16.16-.354.16t-.354-.16zm0-6l-4.246 4.24q-.14.14-.341.153t-.367-.153q-.16-.16-.16-.354t.16-.354l4.221-4.221q.306-.306.733-.306t.733.306l4.22 4.221q.141.14.154.342t-.153.366q-.16.16-.354.16t-.354-.16z");
}

</style>
