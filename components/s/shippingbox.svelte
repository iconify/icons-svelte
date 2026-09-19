<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zdz380bpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="zdz380bpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:shippingbox" {...props}></Icon>
