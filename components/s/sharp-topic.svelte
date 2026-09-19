<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6fwdrb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-topic" {...props}></Icon>
<style>
:global(.z6fwdrb3p) {
  fill: currentColor;
  d: path("m12 6l-2-2H2v16h20V6zm2 10H6v-2h8zm4-4H6v-2h12z");
}

</style>
