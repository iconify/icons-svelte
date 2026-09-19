<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/px5rx3bfu.css';
import '../../css/d/d_4_d11xq.css';
import '../../css/t/tphifsbxc.css';
import '../../css/v/vq3dajbed.css';
import '../../css/y/yeau1bb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="px5rx3bfu"/><path class="d_4_d11xq"/><path class="tphifsbxc"/><path class="vq3dajbed"/><path class="yeau1bb_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:small-shop-alt" {...props}></Icon>
