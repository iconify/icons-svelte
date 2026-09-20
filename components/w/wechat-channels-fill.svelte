<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qhp_tvhii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qhp_tvhii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wechat-channels-fill" {...props}></Icon>
