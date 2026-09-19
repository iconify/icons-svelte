<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnvx83ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnvx83ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:shopping-cart-add" {...props}></Icon>
