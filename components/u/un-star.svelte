<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb64c6bwz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tb64c6bwz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:un-star" {...props}></Icon>
