<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ybcv3hbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":2016};
const content = `<path class="ybcv3hbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:wine" {...props}></Icon>
