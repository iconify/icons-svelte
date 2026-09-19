<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/t/t8tdq3vdl.css';
import '../../css/m/mnjer5bid.css';
import '../../css/e/e7-t_vbov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="t8tdq3vdl"/><rect class="mnjer5bid"/><circle class="e7-t_vbov"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:wallet-outline" {...props}></Icon>
