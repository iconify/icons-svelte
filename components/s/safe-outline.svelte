<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h01tyzbfu.css';
import '../../css/v/vl_s_18va.css';
import '../../css/y/yjdfoebcl.css';
import '../../css/s/sakyh1b-e.css';
import '../../css/l/lf940mbnz.css';
import '../../css/r/rb7olndjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><rect class="vl_s_18va"/><rect class="yjdfoebcl"/><path class="sakyh1b-e"/><circle class="lf940mbnz"/><path class="rb7olndjf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:safe-outline" {...props}></Icon>
