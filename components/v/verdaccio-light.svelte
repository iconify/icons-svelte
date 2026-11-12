<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy_g6_bbi.css';
import '../../css/v/vxr1g-bus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy_g6_bbi"/><path class="vxr1g-bus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:verdaccio-light" {...props}></Icon>
