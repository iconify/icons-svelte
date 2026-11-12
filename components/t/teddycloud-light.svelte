<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd8d_bcwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bd8d_bcwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:teddycloud-light" {...props}></Icon>
