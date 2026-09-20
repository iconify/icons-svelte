<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/l3yrwhb1k.css';
import '../../css/v/vs49djbdr.css';
import '../../css/k/k8gt8ib7o.css';
import '../../css/e/emcs_sbus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l3yrwhb1k"/><path class="vs49djbdr"/><path class="k8gt8ib7o"/><path class="emcs_sbus"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:watch-square-minimalistic-broken" {...props}></Icon>
