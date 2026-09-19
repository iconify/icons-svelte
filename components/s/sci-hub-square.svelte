<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xh4xk2b5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="xh4xk2b5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:sci-hub-square" {...props}></Icon>
