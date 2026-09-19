<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta3t5ry5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="ta3t5ry5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:star" {...props}></Icon>
