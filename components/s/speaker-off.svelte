<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/cay9w4bva.css';
import '../../css/d/dz2lb19zc.css';
import '../../css/a/ahgurpb-c.css';
import '../../css/b/b1n_z_e3z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cay9w4bva"/><path class="dz2lb19zc"/><path class="ahgurpb-c"/><path class="b1n_z_e3z"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons:speaker-off" {...props}></Icon>
