<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cbm0u_bll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cbm0u_bll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:vito" {...props}></Icon>
