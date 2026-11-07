<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sdrg8fy2c.css';
import '../../css/q/qe1jwqbbj.css';
import '../../css/v/v_cqstqlr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sdrg8fy2c"/><path class="qe1jwqbbj"/><path class="v_cqstqlr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-2-linear" {...props}></Icon>
