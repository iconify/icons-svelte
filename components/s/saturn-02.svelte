<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vph1uef-k.css';
import '../../css/v/vghssgbar.css';
import '../../css/w/whlf697ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vph1uef-k"/><path class="vghssgbar"/><path class="whlf697ff"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:saturn-02" {...props}></Icon>
