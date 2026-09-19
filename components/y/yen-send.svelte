<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/o84_2lbma.css';
import '../../css/l/ltfbp1rgr.css';
import '../../css/w/wh4jdubml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="o84_2lbma"/><path class="ltfbp1rgr"/><path class="wh4jdubml"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:yen-send" {...props}></Icon>
