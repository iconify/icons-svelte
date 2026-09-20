<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uwx7xzbau.css';
import '../../css/p/pjoaw5biz.css';
import '../../css/x/xtnbm313d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uwx7xzbau"/><path class="pjoaw5biz"/><path class="xtnbm313d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shopify" {...props}></Icon>
