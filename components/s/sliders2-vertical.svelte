<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv1dzs1tm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yv1dzs1tm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:sliders2-vertical" {...props}></Icon>
