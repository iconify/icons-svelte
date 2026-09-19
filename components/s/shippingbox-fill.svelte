<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txxgc9zxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="txxgc9zxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:shippingbox-fill" {...props}></Icon>
