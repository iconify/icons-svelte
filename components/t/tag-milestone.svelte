<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xriey6b0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="xriey6b0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:tag-milestone" {...props}></Icon>
