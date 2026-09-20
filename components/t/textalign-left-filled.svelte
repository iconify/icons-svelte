<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvdqj146m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wvdqj146m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:textalign-left-filled" {...props}></Icon>
