<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/i/ic7rins_i.css';
import '../../css/b/bl6ucdcay.css';
import '../../css/s/sqndjhubq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ic7rins_i"/><path class="bl6ucdcay"/><path class="sqndjhubq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:telescope-broken" {...props}></Icon>
