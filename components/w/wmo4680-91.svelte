<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq8m6qynl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="pq8m6qynl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wmo4680-91" {...props}></Icon>
