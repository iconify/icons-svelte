<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yc9-v5b7t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yc9-v5b7t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:sub-sandwich-with-steam" {...props}></Icon>
