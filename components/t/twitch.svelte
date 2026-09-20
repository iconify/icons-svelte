<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zin055xwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zin055xwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twitch" {...props}></Icon>
