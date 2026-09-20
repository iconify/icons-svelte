<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9x5pbbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:unichain" {...props}></Icon>
<style>
:global(.m9x5pbbod) {
  fill: var(--svg-color--f50db4, #f50db4);
  d: path("M21 11.829A8.83 8.83 0 0 1 12.171 3h-.342v8.829H3v.342A8.83 8.83 0 0 1 11.829 21h.342v-8.829H21z");
}

</style>
