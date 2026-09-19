<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="skgal-bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:white-medium-square" {...props}></Icon>
<style>
:global(.skgal-bib) {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M8 8h48v48H8z");
}

</style>
