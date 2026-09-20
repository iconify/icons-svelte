<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v97ouibln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v97ouibln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tube" {...props}></Icon>
