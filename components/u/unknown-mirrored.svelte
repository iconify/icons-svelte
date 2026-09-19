<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxpnx9y3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="cxpnx9y3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:unknown-mirrored" {...props}></Icon>
