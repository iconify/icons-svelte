<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1bqggbmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:widget-width-sharp" {...props}></Icon>
<style>
:global(.b1bqggbmr) {
  fill: currentColor;
  d: path("M3 21v-5.077h5.077V21zm6.462 0v-5.077h5.077V21zm6.461 0v-5.077H21V21zM3 14.538V9.462h5.077v5.078zm6.462 0V9.462h5.077v5.078zm6.461 0V9.462H21v5.078zM3 8.077V3h18v5.077z");
}

</style>
