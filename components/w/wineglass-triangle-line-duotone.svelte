<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vb8us5ilq.css';
import '../../css/d/doqa-cbwv.css';
import '../../css/x/xeoh7lbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vb8us5ilq"/><path class="doqa-cbwv"/><path class="xeoh7lbiu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:wineglass-triangle-line-duotone" {...props}></Icon>
