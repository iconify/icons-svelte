<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flen3tbdj.css';
import '../../css/d/dpqjl1opr.css';
import '../../css/j/jwd-jrevq.css';
import '../../css/q/q90b_qbjv.css';
import '../../css/j/j9zbk3bom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="flen3tbdj"><rect transform="rotate(90 16 9)" class="dpqjl1opr"/><rect transform="rotate(90 20 17)" class="jwd-jrevq"/><path class="q90b_qbjv"/><path class="j9zbk3bom"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:subttasks-alt" {...props}></Icon>
