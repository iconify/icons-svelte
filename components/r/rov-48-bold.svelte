<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oatcgvais.css';
import '../../css/l/lm_vypbga.css';
import '../../css/q/q61qoubtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oatcgvais"/><path class="lm_vypbga"/><path class="q61qoubtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rov-48-bold" {...props}></Icon>
