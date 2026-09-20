<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb9r1gbwp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xb9r1gbwp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xpipe-light" {...props}></Icon>
