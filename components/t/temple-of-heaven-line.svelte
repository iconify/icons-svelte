<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnwz1hbhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xnwz1hbhm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:temple-of-heaven-line" {...props}></Icon>
