<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbv87hbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lbv87hbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:satellite" {...props}></Icon>
