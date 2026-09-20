<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrwcnrgva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tab-close-inactive-sharp" {...props}></Icon>
<style>
:global(.mrwcnrgva) {
  fill: currentColor;
  d: path("M14 22v-2h4v2zm-6 0v-2h4v2zM4 10H2V6h2zm0 6H2v-4h2zm2 6H2v-4h2v2h2zm5.9-8.5l2.1-2.1l2.1 2.1l1.4-1.4l-2.1-2.1l2.1-2.1l-1.4-1.4L14 8.6l-2.1-2.1l-1.4 1.4l2.1 2.1l-2.1 2.1zM6 18V2h16v16z");
}

</style>
