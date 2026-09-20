<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pr2h266zm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:slide-link-20-regular" {...props}></Icon>
<style>
:global(.pr2h266zm) {
  fill: currentColor;
  d: path("M13 11.5a.5.5 0 0 1 0 1h-.5a1.5 1.5 0 0 0 0 3h.5a.5.5 0 0 1 0 1h-.5a2.5 2.5 0 0 1 0-5zm3.5 0a2.5 2.5 0 0 1 0 5H16a.5.5 0 0 1 0-1h.5a1.5 1.5 0 0 0 0-3H16a.5.5 0 0 1 0-1zM15 4a3 3 0 0 1 3 3v3.836a3.5 3.5 0 0 0-1-.3V7a2 2 0 0 0-2-2H5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4.146c.107.361.271.698.482 1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3zm1.5 9.5a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1z");
}

</style>
