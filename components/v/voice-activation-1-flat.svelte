<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/a/azxo7r7_y.css';
import '../../css/t/tpemhdl9p.css';
import '../../css/k/kbfndbc2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="azxo7r7_y"/><path class="tpemhdl9p"/><path class="kbfndbc2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:voice-activation-1-flat" {...props}></Icon>
