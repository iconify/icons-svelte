<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ac7w55bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ac7w55bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scraparr-light" {...props}></Icon>
