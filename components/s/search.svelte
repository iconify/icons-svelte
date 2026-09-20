<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3drzyb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j3drzyb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:search" {...props}></Icon>
