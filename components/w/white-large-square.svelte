<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="xszgbmujs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:white-large-square" {...props}></Icon>
<style>
:global(.xszgbmujs) {
  fill: currentColor;
  d: path("M60 4v56H4V4zm2-2H2v60h60z");
}

</style>
