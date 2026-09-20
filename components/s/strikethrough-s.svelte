<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oaay6bb8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oaay6bb8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:strikethrough-s" {...props}></Icon>
