<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yojol6byd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="yojol6byd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-2" {...props}></Icon>
