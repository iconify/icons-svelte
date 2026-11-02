<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dk4n-xbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dk4n-xbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:traffic-lights-line" {...props}></Icon>
