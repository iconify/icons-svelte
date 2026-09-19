<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k31-o_b6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":424,"height":432};
const content = `<path class="k31-o_b6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:slideshare" {...props}></Icon>
