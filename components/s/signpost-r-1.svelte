<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rva42cbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rva42cbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:signpost-r-1" {...props}></Icon>
