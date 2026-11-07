<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fg21p6bqy.css';
import '../../css/r/rycsq4bbm.css';
import '../../css/x/xw09-ubbu.css';
import '../../css/c/cviyaybdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fg21p6bqy"/><path class="rycsq4bbm"/><path class="xw09-ubbu"/><path class="cviyaybdx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:widget-6-broken" {...props}></Icon>
