<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/sgqej7bfm.css';
import '../../css/t/t25li13br.css';
import '../../css/b/bari53b2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sgqej7bfm"/><path class="t25li13br"/><path class="bari53b2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:star-off-line-duotone" {...props}></Icon>
