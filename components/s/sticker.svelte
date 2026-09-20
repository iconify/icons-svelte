<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0-p-2upt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m0-p-2upt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:sticker" {...props}></Icon>
