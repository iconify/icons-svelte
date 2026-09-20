<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph-3zj5qm.css';
import '../../css/p/phy_y3bne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="ph-3zj5qm"/><path clip-rule="evenodd" class="phy_y3bne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:select-cursor-1" {...props}></Icon>
