<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3-xeabwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c3-xeabwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:webcam" {...props}></Icon>
