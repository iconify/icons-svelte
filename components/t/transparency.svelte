<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/r/rhc1809ms.css';
import '../../css/p/pz77t9bmc.css';
import '../../css/a/aclgcfbfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="rhc1809ms"/><path class="pz77t9bmc"/><path class="aclgcfbfw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:transparency" {...props}></Icon>
