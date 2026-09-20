<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_lrdrm-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g_lrdrm-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vidzy-dark" {...props}></Icon>
