<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/m/m_s4vf09q.css';
import '../../css/x/xust17bnz.css';
import '../../css/s/sphoe-x3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="m_s4vf09q"/><path class="xust17bnz"/><path class="sphoe-x3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:saving-wallet-international" {...props}></Icon>
