<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgysx_b2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zgysx_b2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ziit" {...props}></Icon>
