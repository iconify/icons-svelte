<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yzv02bb8d.css';
import '../../css/u/ua2d-bdfl.css';
import '../../css/j/jn4omiblp.css';
import '../../css/n/nsk_fac4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="yzv02bb8d"/><path class="ua2d-bdfl"/><path class="jn4omiblp"/><path class="nsk_fac4d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-kameleon-color:smartphone-qrcode-pop" {...props}></Icon>
