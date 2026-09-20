<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="asdbeh1oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:text-fields-sharp" {...props}></Icon>
<style>
:global(.asdbeh1oc) {
  fill: currentColor;
  d: path("M7 20V7H2V4h13v3h-5v13zm9 0v-8h-3V9h9v3h-3v8z");
}

</style>
