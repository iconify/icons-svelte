<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqyvu54rg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uqyvu54rg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:twake-drive-dark" {...props}></Icon>
