<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7jobn3po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="v7jobn3po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:water-standpipe-with-motor-and-handle-and-drinking-glass" {...props}></Icon>
