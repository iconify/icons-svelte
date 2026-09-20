<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ren4p7bzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ren4p7bzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:truck-delivery-outline" {...props}></Icon>
