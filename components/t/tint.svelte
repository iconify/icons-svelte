<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qghl1qx4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":352,"height":512};
const content = `<path class="qghl1qx4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tint" {...props}></Icon>
