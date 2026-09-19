<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jb1nv6bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="jb1nv6bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:roundedrectangle-outline" {...props}></Icon>
