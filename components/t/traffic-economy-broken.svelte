<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/g/g9i31fsft.css';
import '../../css/d/d992vwbtc.css';
import '../../css/i/izwsa0kiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="g9i31fsft"/><path class="d992vwbtc"/><path class="izwsa0kiq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:traffic-economy-broken" {...props}></Icon>
