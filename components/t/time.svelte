<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdaz6f6ya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="zdaz6f6ya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:time" {...props}></Icon>
