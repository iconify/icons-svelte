<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slg6w6aek.css';
import '../../css/m/mt5r81b_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="slg6w6aek"/><path class="mt5r81b_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:shopping-shipping-weight-kg" {...props}></Icon>
