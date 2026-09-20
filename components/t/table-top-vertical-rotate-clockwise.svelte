<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yak3gxrfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="yak3gxrfd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-vertical-rotate-clockwise" {...props}></Icon>
