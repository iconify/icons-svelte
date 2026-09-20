<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l17g6jb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="l17g6jb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:star" {...props}></Icon>
