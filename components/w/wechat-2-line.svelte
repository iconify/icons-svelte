<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gw-tn0_ls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gw-tn0_ls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wechat-2-line" {...props}></Icon>
