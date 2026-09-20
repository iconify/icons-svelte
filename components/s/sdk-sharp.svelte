<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kn0yajdvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:sdk-sharp" {...props}></Icon>
<style>
:global(.kn0yajdvi) {
  fill: currentColor;
  d: path("M3 21V5.8L5.3 3h13.4L21 5.8V21zM5.4 6h13.2l-.85-1H6.25zm9.8 7.5l-2.1 2.1l1.45 1.45l3.55-3.55l-3.55-3.55l-1.45 1.45zm-6.35 0l2.1-2.1L9.5 9.95L5.95 13.5l3.55 3.55l1.45-1.45z");
}

</style>
