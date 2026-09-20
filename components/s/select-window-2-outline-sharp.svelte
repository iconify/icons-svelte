<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_j4it4yx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:select-window-2-outline-sharp" {...props}></Icon>
<style>
:global(.m_j4it4yx) {
  fill: currentColor;
  d: path("M4 20h12v-9H4zm14-5v-2h2V4H8v5H6V2h16v13zM2 22V9h16v13zm8-6.5");
}

</style>
