<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/x/xq_ez15tr.css';
import '../../css/x/xrw5hkbia.css';
import '../../css/z/zra8kbb3y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="xq_ez15tr"/><path class="xrw5hkbia"/><path class="zra8kbb3y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:worldwide-web-network-www" {...props}></Icon>
