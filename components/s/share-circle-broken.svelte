<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/p3-348ccq.css';
import '../../css/g/gszbesbvo.css';
import '../../css/j/jvpt20bzs.css';
import '../../css/x/xtsqy_b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p3-348ccq"/><path class="gszbesbvo"/><path class="jvpt20bzs"/><path class="xtsqy_b-v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:share-circle-broken" {...props}></Icon>
