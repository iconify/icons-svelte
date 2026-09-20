<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="xb1mfobkx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:sigma-light" {...props}></Icon>
<style>
:global(.xb1mfobkx) {
  fill: currentColor;
  d: path("M186 72V54H76.48l56.21 70.25a6 6 0 0 1 0 7.5L76.48 202H186v-18a6 6 0 0 1 12 0v24a6 6 0 0 1-6 6H64a6 6 0 0 1-4.69-9.75l61-76.25l-61-76.25A6 6 0 0 1 64 42h128a6 6 0 0 1 6 6v24a6 6 0 0 1-12 0");
}

</style>
