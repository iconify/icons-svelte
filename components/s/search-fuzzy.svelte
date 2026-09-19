<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uowvmlswa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uowvmlswa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:search-fuzzy" {...props}></Icon>
