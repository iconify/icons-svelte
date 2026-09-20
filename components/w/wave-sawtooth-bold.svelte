<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="m84zq-amc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ph:wave-sawtooth-bold" {...props}></Icon>
<style>
:global(.m84zq-amc) {
  fill: currentColor;
  d: path("m238.29 138.22l-104 64A12 12 0 0 1 116 192V85.47l-85.71 52.75a12 12 0 0 1-12.58-20.44l104-64A12 12 0 0 1 140 64v106.53l85.71-52.75a12 12 0 1 1 12.58 20.44");
}

</style>
