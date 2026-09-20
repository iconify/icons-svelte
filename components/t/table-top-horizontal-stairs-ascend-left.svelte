<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s83lq0lzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="s83lq0lzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:table-top-horizontal-stairs-ascend-left" {...props}></Icon>
