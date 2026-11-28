<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tlfcv1bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tlfcv1bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:users-x" {...props}></Icon>
