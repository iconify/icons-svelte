<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt3t5jbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":384};
const content = `<path class="xt3t5jbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:view-week" {...props}></Icon>
