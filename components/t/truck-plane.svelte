<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds4-w6bvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="ds4-w6bvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:truck-plane" {...props}></Icon>
