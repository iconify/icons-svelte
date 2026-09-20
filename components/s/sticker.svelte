<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzm8x023o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gzm8x023o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:sticker" {...props}></Icon>
