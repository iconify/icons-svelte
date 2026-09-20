<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyb_fy_my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kyb_fy_my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:wallet-product" {...props}></Icon>
