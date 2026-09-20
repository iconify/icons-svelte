<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/okm5t4bxo.css';
import '../../css/k/kv90-5mju.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="okm5t4bxo"/><path class="kv90-5mju"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:unifi-voucher-site" {...props}></Icon>
