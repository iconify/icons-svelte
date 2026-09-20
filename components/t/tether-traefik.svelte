<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrl71abcz.css';
import '../../css/i/ilzd2fb8z.css';
import '../../css/a/afvuxlb2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<linearGradient id="SVG1IsLgDEn" x1="93.945" x2="163.305" y1="256" y2="256" gradientUnits="userSpaceOnUse"><stop offset="0" class="xrl71abcz"/><stop offset="1" class="ilzd2fb8z"/></linearGradient><path fill="url(#SVG1IsLgDEn)" class="afvuxlb2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tether-traefik" {...props}></Icon>
