<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tad0vib8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stockpot-sharp" {...props}></Icon>
<style>
:global(.tad0vib8r) {
  fill: currentColor;
  d: path("M4 19V7.98h16V19zM4 6.596v-1h5.5V4h5v1.596H20v1z");
}

</style>
