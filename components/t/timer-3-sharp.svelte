<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibfk2gb2y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:timer-3-sharp" {...props}></Icon>
<style>
:global(.ibfk2gb2y) {
  fill: currentColor;
  d: path("M8 19v-3h6v-2.5H9v-3h5V8H8V5h9v5.5L15.5 12l1.5 1.5V19z");
}

</style>
