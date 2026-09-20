<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzrvxn7px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:wiken" {...props}></Icon>
<style>
:global(.tzrvxn7px) {
  fill: var(--svg-color--474747, #474747);
  d: path("M3 7.929h18l-6.6 8.143l-2.4-2.91l-2.4 2.91zm11.417 6l4.226-4.715H5.357l4.226 4.715L12 11.357z");
}

</style>
