<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/j/j79gsgb3b.css';
import '../../css/b/bg5-es3pu.css';
import '../../css/s/silx_qdiv.css';
import '../../css/x/xrtu0pbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="j79gsgb3b"/><path class="bg5-es3pu"/><path class="silx_qdiv"/><path class="xrtu0pbiv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:store-location-02" {...props}></Icon>
