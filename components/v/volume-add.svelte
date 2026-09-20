<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/np8zppb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="np8zppb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:volume-add" {...props}></Icon>
