<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbzm_tbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbzm_tbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:tiktok-logo" {...props}></Icon>
