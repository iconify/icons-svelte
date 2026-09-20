<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9jl1r7rh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j9jl1r7rh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:stamp-outline" {...props}></Icon>
