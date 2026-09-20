<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jc5s3ebqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:video-32-filled" {...props}></Icon>
<style>
:global(.jc5s3ebqf) {
  fill: currentColor;
  d: path("M2 10.5A4.5 4.5 0 0 1 6.5 6h10a4.5 4.5 0 0 1 4.5 4.5v11a4.5 4.5 0 0 1-4.5 4.5h-10A4.5 4.5 0 0 1 2 21.5zm27.996-.746c0-1.814-2.036-2.882-3.529-1.852l-3.967 2.74v10.716l3.968 2.74c1.492 1.03 3.528-.038 3.528-1.852z");
}

</style>
