<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/thh11x-om.css';
import '../../css/p/pd3wy4zwc.css';
import '../../css/n/nf3olcpnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="thh11x-om"/><path class="pd3wy4zwc"/><path class="nf3olcpnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:speedometer-48-bold" {...props}></Icon>
