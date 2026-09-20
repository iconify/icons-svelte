<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quzxhsgmn.css';
import '../../css/o/o3q9lk3_p.css';
import '../../css/n/nw-hxrxlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="quzxhsgmn"/><path class="o3q9lk3_p"/><path class="nw-hxrxlx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vouchervault" {...props}></Icon>
