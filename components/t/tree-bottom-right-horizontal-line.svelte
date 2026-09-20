<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlrndbbwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zlrndbbwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tree-bottom-right-horizontal-line" {...props}></Icon>
