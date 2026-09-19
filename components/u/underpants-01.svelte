<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/l/lpx5w1bem.css';
import '../../css/u/ux20bf5oc.css';
import '../../css/g/g5fsc_b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lpx5w1bem"/><path class="ux20bf5oc"/><path class="g5fsc_b7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:underpants-01" {...props}></Icon>
