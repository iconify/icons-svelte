<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yd5n43due.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yd5n43due"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:stopwatch-16" {...props}></Icon>
