<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3-k1fbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="p3-k1fbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:w-square" {...props}></Icon>
