<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/kfclpjb6w.css';
import '../../css/k/kvqhqh57h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="kfclpjb6w"/><path class="kvqhqh57h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-keyhole-minimalistic-broken" {...props}></Icon>
