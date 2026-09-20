<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/f/fnklneb_k.css';
import '../../css/k/kiol6ablm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><rect transform="rotate(45 15.712 1.924)" class="fnklneb_k"/><path class="kiol6ablm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:ruler-diagonal" {...props}></Icon>
