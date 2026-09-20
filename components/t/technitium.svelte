<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dx_xolb0l.css';
import '../../css/n/nfhumnbud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dx_xolb0l"/><path class="nfhumnbud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:technitium" {...props}></Icon>
