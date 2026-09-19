<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-keh5bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="n-keh5bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:share-alt" {...props}></Icon>
