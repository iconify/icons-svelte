<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjc4pcc3n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pjc4pcc3n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wechat-pay-fill" {...props}></Icon>
