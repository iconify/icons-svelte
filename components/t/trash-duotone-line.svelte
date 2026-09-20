<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unc2embyj.css';
import '../../css/u/uispwaboz.css';
import '../../css/i/iwunlbmzw.css';
import '../../css/v/v00gusbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="unc2embyj"><path class="uispwaboz"/><path class="iwunlbmzw"/><path class="v00gusbyh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:trash-duotone-line" {...props}></Icon>
