<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq9hgpdsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xq9hgpdsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:surveillance-filled" {...props}></Icon>
