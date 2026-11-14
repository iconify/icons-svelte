<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovixjvzyc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:warning-sign-blank" {...props}></Icon>
<style>
:global(.ovixjvzyc) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.966 6.892l5.088 9.373q.915 1.687-.066 3.336t-2.9 1.649H6.912q-1.919 0-2.9-1.649t-.066-3.336l5.088-9.373Q9.992 5.127 12 5.127t2.966 1.765");
}

</style>
