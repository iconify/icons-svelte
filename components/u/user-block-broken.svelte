<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dtl23o_xq.css';
import '../../css/n/nuv1qz_2q.css';
import '../../css/v/v9_s5dbjh.css';
import '../../css/x/xjh3njbok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="dtl23o_xq"/><path class="nuv1qz_2q"/><path class="v9_s5dbjh"/><circle class="xjh3njbok"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:user-block-broken" {...props}></Icon>
