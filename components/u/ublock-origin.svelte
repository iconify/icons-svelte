<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn_etb2ed.css';
import '../../css/a/aoms7-zgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xn_etb2ed"/><path class="aoms7-zgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ublock-origin" {...props}></Icon>
