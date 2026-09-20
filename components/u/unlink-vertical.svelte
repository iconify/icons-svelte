<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d82qtqb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="d82qtqb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:unlink-vertical" {...props}></Icon>
