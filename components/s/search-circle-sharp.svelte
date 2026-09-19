<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4pi1pb2y.css';
import '../../css/p/pxs3yikcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="k4pi1pb2y"/><circle class="pxs3yikcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:search-circle-sharp" {...props}></Icon>
