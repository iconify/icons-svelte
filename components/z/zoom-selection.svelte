<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipaqwylxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ipaqwylxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:zoom-selection" {...props}></Icon>
