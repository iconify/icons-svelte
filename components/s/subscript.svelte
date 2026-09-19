<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp2y7_blq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="jp2y7_blq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:subscript" {...props}></Icon>
