<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kewrg803m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kewrg803m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:voucher-outline" {...props}></Icon>
