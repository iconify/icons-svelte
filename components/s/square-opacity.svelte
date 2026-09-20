<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xui-nrbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xui-nrbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:square-opacity" {...props}></Icon>
