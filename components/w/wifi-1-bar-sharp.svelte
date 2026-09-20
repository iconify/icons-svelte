<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2dq2wbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:wifi-1-bar-sharp" {...props}></Icon>
<style>
:global(.z2dq2wbpl) {
  fill: currentColor;
  d: path("m12 21l-2.448-2.454q.486-.486 1.119-.747q.633-.26 1.327-.26t1.329.26t1.121.747z");
}

</style>
