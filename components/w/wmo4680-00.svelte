<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f25ju-b2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="f25ju-b2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wmo4680-00" {...props}></Icon>
