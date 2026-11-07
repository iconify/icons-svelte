<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/f7guqx38x.css';
import '../../css/w/wo5j09bdc.css';
import '../../css/y/yt8px34lk.css';
import '../../css/v/vciis7brh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f7guqx38x"/><path class="wo5j09bdc"/><path class="yt8px34lk"/><path class="vciis7brh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:smart-home-broken" {...props}></Icon>
