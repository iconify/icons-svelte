<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gle8jacmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gle8jacmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-miniprogram-fill" {...props}></Icon>
