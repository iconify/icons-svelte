<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv22wab9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zv22wab9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:transmission-dark" {...props}></Icon>
