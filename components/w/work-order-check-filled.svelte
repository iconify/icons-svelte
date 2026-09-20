<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip3d1v6sl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ip3d1v6sl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:work-order-check-filled" {...props}></Icon>
