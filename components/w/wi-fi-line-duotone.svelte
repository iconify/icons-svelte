<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dt_kzxb6g.css';
import '../../css/f/focqhos4p.css';
import '../../css/g/g1pa1nbfl.css';
import '../../css/z/zj2p4py0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dt_kzxb6g"/><path class="focqhos4p"/><path class="g1pa1nbfl"/><path class="zj2p4py0y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wi-fi-line-duotone" {...props}></Icon>
