<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sycvawb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token-branded:waves" {...props}></Icon>
<style>
:global(.sycvawb1d) {
  fill: var(--svg-color--1857f5, #1857f5);
  d: path("m3 12l9-9l9 9l-9 9z");
}

</style>
