<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/t/thfih0jyl.css';
import '../../css/e/elhf-ac1v.css';
import '../../css/b/bwd60po_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="thfih0jyl"/><path class="elhf-ac1v"/><path class="bwd60po_v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:triangle-01" {...props}></Icon>
