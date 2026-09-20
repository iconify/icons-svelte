<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5u6gbbk.css';
import '../../css/f/f-4f0ug2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xg5u6gbbk"/><path class="f-4f0ug2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-venus" {...props}></Icon>
