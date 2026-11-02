<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz-c0x2vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz-c0x2vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ship-line" {...props}></Icon>
