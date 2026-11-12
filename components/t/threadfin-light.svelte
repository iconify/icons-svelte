<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xus3r2plp.css';
import '../../css/u/u9q951uce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xus3r2plp"/><path class="u9q951uce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:threadfin-light" {...props}></Icon>
