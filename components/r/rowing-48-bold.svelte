<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfamm_bud.css';
import '../../css/m/mg071ztjv.css';
import '../../css/n/nxyg22omp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tfamm_bud"/><path class="mg071ztjv"/><path class="nxyg22omp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rowing-48-bold" {...props}></Icon>
