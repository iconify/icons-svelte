<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sb7y0rb1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="sb7y0rb1q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:steak-light" {...props}></Icon>
