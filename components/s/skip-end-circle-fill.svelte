<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjeuv2d3b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qjeuv2d3b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:skip-end-circle-fill" {...props}></Icon>
