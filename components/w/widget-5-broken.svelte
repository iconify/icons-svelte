<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fgrp_1b7a.css';
import '../../css/r/r01r-3bes.css';
import '../../css/w/wko_7ccxa.css';
import '../../css/o/o8ptejdcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fgrp_1b7a"/><path class="r01r-3bes"/><path class="wko_7ccxa"/><path class="o8ptejdcw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-5-broken" {...props}></Icon>
