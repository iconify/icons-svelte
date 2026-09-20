<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic-heh8qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stockpot-outline-sharp" {...props}></Icon>
<style>
:global(.ic-heh8qg) {
  fill: currentColor;
  d: path("M4 19V7.98h16V19zm1-1h14V8.98H5zM4 6.596v-1h5.5V4h5v1.596H20v1zm8 6.885");
}

</style>
