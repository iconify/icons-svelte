<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwhlflb8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wwhlflb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star-and-crescent" {...props}></Icon>
