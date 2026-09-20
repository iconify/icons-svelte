<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn7-mf9wj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-timeline-sharp" {...props}></Icon>
<style>
:global(.kn7-mf9wj) {
  fill: currentColor;
  d: path("M4 20V4h16v16zm2.539-3.5h4.923v-1H6.539zm6-8h4.923v-1h-4.923zm-3 4h4.923v-1H9.539z");
}

</style>
