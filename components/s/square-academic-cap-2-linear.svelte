<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/h/hw8sv4bga.css';
import '../../css/b/bubvahb-l.css';
import '../../css/c/csckydbbl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="hw8sv4bga"/><path class="bubvahb-l"/><path class="csckydbbl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:square-academic-cap-2-linear" {...props}></Icon>
