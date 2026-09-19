<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xv2khxbzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xv2khxbzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:tram" {...props}></Icon>
