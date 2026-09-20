<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cg0jxcbxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cg0jxcbxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:undo-icon" {...props}></Icon>
