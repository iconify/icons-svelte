<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xld-v2bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xld-v2bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:xxl-sports-dark" {...props}></Icon>
