<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g04pd3blf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:settings-cell-sharp" {...props}></Icon>
<style>
:global(.g04pd3blf) {
  fill: currentColor;
  d: path("M8 23.77q-.31 0-.54-.23T7.23 23t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23m4 0q-.31 0-.54-.23t-.23-.54t.23-.54t.54-.23t.54.23t.23.54t-.23.54t-.54.23M6.808 19V1h10.384v18zm1-3.5h8.384v-11H7.808z");
}

</style>
