<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ykmzjjlqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:shift-sharp" {...props}></Icon>
<style>
:global(.ykmzjjlqy) {
  fill: currentColor;
  d: path("M8 21v-8H3l9-11l9 11h-5v8z");
}

</style>
