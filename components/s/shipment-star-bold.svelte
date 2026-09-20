<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywkgkr1pi.css';
import '../../css/s/slgmhktay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ywkgkr1pi"/><path class="slgmhktay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipment-star-bold" {...props}></Icon>
