<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":222};
const content = `<path class="gzzr1mstp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:vercel-icon" {...props}></Icon>
<style>
:global(.gzzr1mstp) {
  d: path("m128 0l128 221.705H0z");
}

</style>
