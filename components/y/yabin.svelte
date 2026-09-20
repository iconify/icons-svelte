<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk_y2-bpv.css';
import '../../css/k/k7rs5ub2m.css';
import '../../css/b/ba7212etj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bk_y2-bpv"/><path class="k7rs5ub2m"/><path class="ba7212etj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yabin" {...props}></Icon>
