<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q--72vv7c.css';
import '../../css/c/cz0r6uwoz.css';
import '../../css/n/nf5-akdhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q--72vv7c"/><path class="cz0r6uwoz"/><path class="nf5-akdhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:shipping-logistic-free-shipping-delivery-truck-bold" {...props}></Icon>
