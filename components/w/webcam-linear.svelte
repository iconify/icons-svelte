<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/q/qgu7_ebsb.css';
import '../../css/k/kva043bzk.css';
import '../../css/t/t26d7g3rg.css';
import '../../css/p/pf1ifwbeb.css';
import '../../css/y/y-9fctbqs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="qgu7_ebsb"/><path class="kva043bzk"/><path class="t26d7g3rg"/><path class="pf1ifwbeb"/><path class="y-9fctbqs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:webcam-linear" {...props}></Icon>
