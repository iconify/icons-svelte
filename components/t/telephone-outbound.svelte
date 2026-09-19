<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-ux0x7wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d-ux0x7wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:telephone-outbound" {...props}></Icon>
