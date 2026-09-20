<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cyegxbcig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cyegxbcig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:shipping-fast-solid" {...props}></Icon>
