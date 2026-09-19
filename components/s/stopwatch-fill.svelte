<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws9c__bwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ws9c__bwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:stopwatch-fill" {...props}></Icon>
