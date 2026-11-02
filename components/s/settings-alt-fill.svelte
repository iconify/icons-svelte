<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0jr7lbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:settings-alt-fill" {...props}></Icon>
<style>
:global(.m0jr7lbdu) {
  fill: currentColor;
  d: path("m19.342 18.447l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236v7.528a3 3 0 0 1-1.658 2.683M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
