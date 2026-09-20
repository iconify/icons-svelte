<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/c/cpx6cvtmg.css';
import '../../css/k/knuyjfb2y.css';
import '../../css/n/n95nkccdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cpx6cvtmg"/><path class="knuyjfb2y"/><path class="n95nkccdu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mage:trophy-star" {...props}></Icon>
