<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqg2i0b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="rqg2i0b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:tv" {...props}></Icon>
