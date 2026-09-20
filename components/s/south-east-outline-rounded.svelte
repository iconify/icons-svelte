<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dzu95zeui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:south-east-outline-rounded" {...props}></Icon>
<style>
:global(.dzu95zeui) {
  fill: currentColor;
  d: path("M16.292 17L5.354 6.062q-.14-.14-.15-.345q-.01-.203.15-.363t.354-.16t.354.16L17 16.292V9.5q0-.213.143-.357T17.5 9t.357.143T18 9.5v7.692q0 .349-.23.578t-.578.23H9.5q-.213 0-.357-.143T9 17.5t.143-.357T9.5 17z");
}

</style>
