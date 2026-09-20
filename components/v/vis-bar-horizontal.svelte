<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jli5rnb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="jli5rnb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:vis-bar-horizontal" {...props}></Icon>
