<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9-0a9t5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:unarchive-outline-sharp" {...props}></Icon>
<style>
:global(.o9-0a9t5o) {
  fill: currentColor;
  d: path("m12 10l-4 4l1.4 1.4l1.6-1.6V18h2v-4.2l1.6 1.6L16 14zM5 8v11h14V8zM3 21V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25zm6.6 7.5");
}

</style>
