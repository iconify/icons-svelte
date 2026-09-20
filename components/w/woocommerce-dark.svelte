<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6n9e2slx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x6n9e2slx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:woocommerce-dark" {...props}></Icon>
