<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j76p0in1i.css';
import '../../css/t/ttc468btu.css';
import '../../css/u/uii4avzkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j76p0in1i"/><circle class="ttc468btu"/><circle class="uii4avzkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:shopping-cart-outline" {...props}></Icon>
