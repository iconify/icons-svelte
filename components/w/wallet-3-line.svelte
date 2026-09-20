<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i_gnn0bpn.css';
import '../../css/z/zq43phuqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i_gnn0bpn"/><path class="zq43phuqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wallet-3-line" {...props}></Icon>
