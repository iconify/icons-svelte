<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/guysevb9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="guysevb9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tooljet-dark" {...props}></Icon>
