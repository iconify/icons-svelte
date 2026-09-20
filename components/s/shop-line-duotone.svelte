<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/j/jaz9c-b0o.css';
import '../../css/z/zj2nirlnt.css';
import '../../css/z/zwtdkobff.css';
import '../../css/b/bppk80h1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="jaz9c-b0o"/><path class="zj2nirlnt"/><path class="zwtdkobff"/><path class="bppk80h1t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shop-line-duotone" {...props}></Icon>
