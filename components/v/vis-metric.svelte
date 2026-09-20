<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gi6to1cst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gi6to1cst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-metric" {...props}></Icon>
