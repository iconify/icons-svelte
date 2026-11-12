<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yeo-qubjb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yeo-qubjb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:system76-light" {...props}></Icon>
