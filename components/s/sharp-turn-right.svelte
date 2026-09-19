<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yw6av6bjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-turn-right" {...props}></Icon>
<style>
:global(.yw6av6bjx) {
  fill: currentColor;
  d: path("m17.17 11l-1.58 1.59L17 14l4-4l-4-4l-1.41 1.41L17.17 9H7v11h2v-9z");
}

</style>
