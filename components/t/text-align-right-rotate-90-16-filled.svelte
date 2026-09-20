<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="kgrs7y7ae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-right-rotate-90-16-filled" {...props}></Icon>
<style>
:global(.kgrs7y7ae) {
  fill: currentColor;
  d: path("M12.25 5a.75.75 0 0 1 .75.75v8.5a.75.75 0 0 1-1.5 0v-8.5a.75.75 0 0 1 .75-.75m-4-4a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-1.5 0V1.75A.75.75 0 0 1 8.25 1m-4 8a.75.75 0 0 1 .75.75v4.5a.75.75 0 0 1-1.5 0v-4.5A.75.75 0 0 1 4.25 9");
}

</style>
