<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ninrxlcbc.css';
import '../../css/w/wg1goqjvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ninrxlcbc"/><path class="wg1goqjvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:uncloud" {...props}></Icon>
