<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pz9flcc9s.css';
import '../../css/v/vwqq1x5bt.css';
import '../../css/y/yt3p9tmeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pz9flcc9s"/><path class="vwqq1x5bt"/><path class="yt3p9tmeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:separator-vertical-bold" {...props}></Icon>
