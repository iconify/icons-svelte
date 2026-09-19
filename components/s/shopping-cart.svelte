<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ive6bserv.css';
import '../../css/u/ur8mbpnqr.css';
import '../../css/n/nxheq_lap.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<circle class="ive6bserv"/><circle class="ur8mbpnqr"/><path class="nxheq_lap"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:shopping-cart" {...props}></Icon>
