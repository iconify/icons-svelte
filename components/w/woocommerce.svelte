<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8fh6bcax.css';
import '../../css/b/bxc0s0-hm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s8fh6bcax"/><path class="bxc0s0-hm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:woocommerce" {...props}></Icon>
