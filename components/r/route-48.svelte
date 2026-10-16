<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/em_gclcem.css';
import '../../css/n/nfttrft0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="em_gclcem"/><path class="nfttrft0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:route-48" {...props}></Icon>
