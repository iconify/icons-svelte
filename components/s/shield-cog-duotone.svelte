<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w6hp2xf_p.css';
import '../../css/i/ioa1vxxno.css';
import '../../css/r/rmdxzccvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="w6hp2xf_p"/><path class="ioa1vxxno"/><path class="rmdxzccvt"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:shield-cog-duotone" {...props}></Icon>
