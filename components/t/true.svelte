<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb-2542dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="yb-2542dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:true" {...props}></Icon>
