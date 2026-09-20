<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfs-gz07l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bfs-gz07l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:tricentis" {...props}></Icon>
