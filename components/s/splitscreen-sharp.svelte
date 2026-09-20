<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uioqj7bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:splitscreen-sharp" {...props}></Icon>
<style>
:global(.uioqj7bms) {
  fill: currentColor;
  d: path("M4 10.635V4h16v6.635zM4 20v-6.615h16V20z");
}

</style>
