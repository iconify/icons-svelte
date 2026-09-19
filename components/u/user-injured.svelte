<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqwqnlb_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="sqwqnlb_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:user-injured" {...props}></Icon>
