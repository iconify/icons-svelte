<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbeo8hb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xbeo8hb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tasterr-dark" {...props}></Icon>
