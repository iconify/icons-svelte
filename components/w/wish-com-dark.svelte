<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxd672bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yxd672bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:wish-com-dark" {...props}></Icon>
