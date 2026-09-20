<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-l7bsb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r-l7bsb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unifi-voucher-site-dark" {...props}></Icon>
