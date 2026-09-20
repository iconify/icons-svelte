<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlsql2bgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dlsql2bgp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:stalwart-light" {...props}></Icon>
