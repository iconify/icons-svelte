<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvka3bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddvka3bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:usb-line" {...props}></Icon>
