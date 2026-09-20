<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yimgu8b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yimgu8b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:screw-beside-nail" {...props}></Icon>
