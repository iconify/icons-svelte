<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzvl6-gkr.css';
import '../../css/x/x-s9mn_cg.css';
import '../../css/r/r83jtnbma.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nzvl6-gkr"/><path class="x-s9mn_cg"/><path class="r83jtnbma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:smart-charging-48" {...props}></Icon>
