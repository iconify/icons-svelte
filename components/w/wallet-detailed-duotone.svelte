<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/t24kg-brs.css';
import '../../css/t/ti-0kubfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="t24kg-brs"/><path class="ti-0kubfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:wallet-detailed-duotone" {...props}></Icon>
