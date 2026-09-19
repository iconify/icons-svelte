<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/bvzr0fklu.css';
import '../../css/l/lll6g396l.css';
import '../../css/g/gyj__2tko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bvzr0fklu"/><path class="lll6g396l"/><path class="gyj__2tko"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tea" {...props}></Icon>
