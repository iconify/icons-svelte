<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hws41otvx.css';
import '../../css/d/dplkn_mxv.css';
import '../../css/f/fhnye3b1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hws41otvx"/><path class="dplkn_mxv"/><path class="fhnye3b1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-ring-broken" {...props}></Icon>
