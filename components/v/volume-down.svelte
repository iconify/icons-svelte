<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yez44b7jj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yez44b7jj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:volume-down" {...props}></Icon>
