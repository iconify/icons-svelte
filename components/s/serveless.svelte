<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":375};
const content = `<path class="xpaw3gbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:serveless" {...props}></Icon>
<style>
:global(.xpaw3gbpy) {
  fill: var(--svg-color--ffd426, #FFD426);
  d: path("M0 218.14l119.805-16.955l-105.676 173.49l240.742-217.569l-103.984 10.172L256 0z");
}

</style>
