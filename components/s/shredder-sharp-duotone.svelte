<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/f/fm23tlb2v.css';
import '../../css/q/qo3g9rbnz.css';
import '../../css/v/vcg_lradd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fm23tlb2v"/><path clip-rule="evenodd" class="qo3g9rbnz"/><path class="vcg_lradd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:shredder-sharp-duotone" {...props}></Icon>
