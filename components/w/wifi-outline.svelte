<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chl3e-b8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":504,"height":400};
const content = `<path class="chl3e-b8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:wifi-outline" {...props}></Icon>
