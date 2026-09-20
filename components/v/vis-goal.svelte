<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1l5eab0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j1l5eab0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-goal" {...props}></Icon>
