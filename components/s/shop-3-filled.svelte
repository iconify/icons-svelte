<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pq7ufdtte.css';
import '../../css/j/jb-34lb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pq7ufdtte"/><path class="jb-34lb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:shop-3-filled" {...props}></Icon>
