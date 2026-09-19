<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bt__3t6bm.css';
import '../../css/j/j9gaom6_i.css';
import '../../css/c/cnc8kxp4p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bt__3t6bm"/><circle class="j9gaom6_i"/><circle class="cnc8kxp4p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:tangent" {...props}></Icon>
