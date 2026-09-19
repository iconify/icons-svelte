<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq32-81to.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xq32-81to"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:search" {...props}></Icon>
