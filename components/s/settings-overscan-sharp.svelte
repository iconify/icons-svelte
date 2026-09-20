<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b3wpgbbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:settings-overscan-sharp" {...props}></Icon>
<style>
:global(.b3wpgbbfy) {
  fill: currentColor;
  d: path("M7 14v-4l-2 2zm5 3l2-2h-4zm-2-8h4l-2-2zm7 5l2-2l-2-2zM2 20V4h20v16z");
}

</style>
