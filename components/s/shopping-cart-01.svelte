<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt6gvib0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lt6gvib0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:shopping-cart-01" {...props}></Icon>
