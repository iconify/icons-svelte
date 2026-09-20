<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ksc5z13bv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ksc5z13bv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:utorrent-light" {...props}></Icon>
