<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xvjk-cbox.css';
import '../../css/u/u_u9u_b6m.css';
import '../../css/p/p7exz8bqd.css';
import '../../css/z/zwiw2-bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="u_u9u_b6m"/><path class="p7exz8bqd"/><path class="zwiw2-bkv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:streets-map-point-linear" {...props}></Icon>
