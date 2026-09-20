<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kv_3vhb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kv_3vhb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wireguard-dark" {...props}></Icon>
