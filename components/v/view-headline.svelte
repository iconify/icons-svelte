<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sqduyhbgk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:view-headline" {...props}></Icon>
<style>
:global(.sqduyhbgk) {
  fill: currentColor;
  d: path("M4 15h16v-2H4zm0 4h16v-2H4zm0-8h16V9H4zm0-6v2h16V5z");
}

</style>
