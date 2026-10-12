<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fd10_3lgv.css';
import '../../css/u/uo2fs-9le.css';
import '../../css/n/nvpqntokq.css';
import '../../css/g/gkp75vytj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fd10_3lgv"/><path class="uo2fs-9le"/><path class="nvpqntokq"/><path class="gkp75vytj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:valve-wheel-48" {...props}></Icon>
