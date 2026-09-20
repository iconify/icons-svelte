<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oat-qbbrm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="oat-qbbrm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tiktok-dark" {...props}></Icon>
