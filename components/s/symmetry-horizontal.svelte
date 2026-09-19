<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybq-wfveb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ybq-wfveb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:symmetry-horizontal" {...props}></Icon>
