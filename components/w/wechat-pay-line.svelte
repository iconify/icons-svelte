<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuq0-yb1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuq0-yb1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-pay-line" {...props}></Icon>
