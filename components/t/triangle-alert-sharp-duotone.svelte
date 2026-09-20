<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/o/oaf72vz_i.css';
import '../../css/q/qf7tbcbyb.css';
import '../../css/j/ju8v6k8zc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="oaf72vz_i"/><path class="qf7tbcbyb"/><path class="ju8v6k8zc"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangle-alert-sharp-duotone" {...props}></Icon>
