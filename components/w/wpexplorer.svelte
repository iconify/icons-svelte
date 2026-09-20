<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx3-z3b_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vx3-z3b_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:wpexplorer" {...props}></Icon>
