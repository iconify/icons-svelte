<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmy6ybc5p.css';
import '../../css/q/qwbk6jhrs.css';
import '../../css/z/z-hfbnbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="pmy6ybc5p"/><path class="qwbk6jhrs"/><circle class="z-hfbnbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:telltaledns" {...props}></Icon>
