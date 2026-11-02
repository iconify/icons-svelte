<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z8t01ccwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z8t01ccwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:usb-flash-disk-line" {...props}></Icon>
