<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kycuecjmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="kycuecjmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:trending-down" {...props}></Icon>
