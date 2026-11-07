<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/z/zf6m_rg7v.css';
import '../../css/d/dv86dk8ai.css';
import '../../css/t/t3tivrbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="zf6m_rg7v"/><path class="dv86dk8ai"/><path class="t3tivrbho"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:tag-price-broken" {...props}></Icon>
