<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dm2oz9bnr.css';
import '../../css/y/yv44zccgq.css';
import '../../css/t/t-og4eyuq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dm2oz9bnr"/><path class="yv44zccgq"/><path class="t-og4eyuq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skirt-broken" {...props}></Icon>
