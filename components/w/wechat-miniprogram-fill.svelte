<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yzsz40bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yzsz40bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-miniprogram-fill" {...props}></Icon>
