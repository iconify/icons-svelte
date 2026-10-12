<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/afarpnbpz.css';
import '../../css/h/hs_7v4d8f.css';
import '../../css/m/mxdyr1b6x.css';
import '../../css/p/pvoalybxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="afarpnbpz"/><path class="hs_7v4d8f"/><path class="mxdyr1b6x"/><path class="pvoalybxg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:vegan-duotone" {...props}></Icon>
