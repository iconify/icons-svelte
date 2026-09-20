<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq_ifjq_u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lq_ifjq_u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tpdb-dark" {...props}></Icon>
