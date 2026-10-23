<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhf967wag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhf967wag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:separator-horizontal" {...props}></Icon>
