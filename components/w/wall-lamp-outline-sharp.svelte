<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgvx1jbso"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:wall-lamp-outline-sharp" {...props}></Icon>
<style>
:global(.tgvx1jbso) {
  fill: currentColor;
  d: path("M3.73 20v-5h1v5zm4.62-8h9.3l-1.8-6h-5.7zm0 0h9.3zM6.5 18v-1h6v-4H6.996L9.4 5h7.2l2.404 8H13.5v5z");
}

</style>
