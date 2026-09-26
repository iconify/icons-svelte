<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i__5tx9hs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="i__5tx9hs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stepzen-graph-server" {...props}></Icon>
