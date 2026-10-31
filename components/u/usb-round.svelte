<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlro9p6ts.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlro9p6ts"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:usb-round" {...props}></Icon>
