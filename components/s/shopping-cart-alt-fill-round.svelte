<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy4cxcjtv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xy4cxcjtv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:shopping-cart-alt-fill-round" {...props}></Icon>
