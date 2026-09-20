<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sjkbmacej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sjkbmacej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-miniprogram-line" {...props}></Icon>
