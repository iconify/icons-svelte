<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xul90ei0n.css';
import '../../css/x/x9u4_etvk.css';
import '../../css/z/z7l_f7r4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xul90ei0n"/><circle class="x9u4_etvk"/><circle class="z7l_f7r4c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:skateboard-line-duotone" {...props}></Icon>
