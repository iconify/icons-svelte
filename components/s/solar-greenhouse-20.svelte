<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czmnpfbuv.css';
import '../../css/v/vy9zp_bkd.css';
import '../../css/h/h1yn6ab_j.css';
import '../../css/n/n5omxc2qq.css';
import '../../css/m/mrtw_lq_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="czmnpfbuv"/><path class="vy9zp_bkd"/><path class="h1yn6ab_j"/><path class="n5omxc2qq"/><path class="mrtw_lq_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-greenhouse-20" {...props}></Icon>
