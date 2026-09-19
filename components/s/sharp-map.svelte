<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z0mbrxbfg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-map" {...props}></Icon>
<style>
:global(.z0mbrxbfg) {
  fill: currentColor;
  d: path("M15 5.1L9 3L3 5.02v16.2l6-2.33l6 2.1l6-2.02V2.77zm0 13.79l-6-2.11V5.11l6 2.11z");
}

</style>
