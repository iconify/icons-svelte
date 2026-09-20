<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoq87o7cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xoq87o7cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:wheelie-bin-and-drink-bottle-and-can" {...props}></Icon>
