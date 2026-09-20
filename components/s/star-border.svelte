<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqf1fgczx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqf1fgczx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:star-border" {...props}></Icon>
