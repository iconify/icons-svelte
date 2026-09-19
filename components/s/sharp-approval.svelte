<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oxrb5nb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-approval" {...props}></Icon>
<style>
:global(.oxrb5nb_m) {
  fill: currentColor;
  d: path("M4 14v8h16v-8zm14 4H6v-2h12zM12 2C9.24 2 7 4.24 7 7l5 7l5-7c0-2.76-2.24-5-5-5");
}

</style>
