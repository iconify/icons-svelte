<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pr52f_b5y.css';
import '../../css/j/j4ml71b0k.css';
import '../../css/o/on6khhbhh.css';
import '../../css/t/ti3g_bcpn.css';
import '../../css/q/qryul2gig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="pr52f_b5y"><path class="j4ml71b0k"/><path class="on6khhbhh"/><path class="ti3g_bcpn"/><path class="qryul2gig"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-fall-broken" {...props}></Icon>
