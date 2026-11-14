<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lc6h766dc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lc6h766dc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:swarmpit-dark" {...props}></Icon>
