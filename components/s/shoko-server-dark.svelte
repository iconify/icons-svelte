<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3-y7_b1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x3-y7_b1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:shoko-server-dark" {...props}></Icon>
