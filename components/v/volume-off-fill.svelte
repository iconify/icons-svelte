<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdkq4lblu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fdkq4lblu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:volume-off-fill" {...props}></Icon>
