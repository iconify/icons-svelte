<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j85y1pb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="j85y1pb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:stardust-above-outstretched-hand" {...props}></Icon>
