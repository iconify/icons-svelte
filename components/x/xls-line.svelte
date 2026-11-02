<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ev3r4g_nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ev3r4g_nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:xls-line" {...props}></Icon>
