<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ai-1qvthx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ai-1qvthx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:triangles-left-right-in-wide-rounded-rectangle-outline" {...props}></Icon>
