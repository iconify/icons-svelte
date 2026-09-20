<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k1_2fvbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="k1_2fvbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:wallet-purse-solid" {...props}></Icon>
