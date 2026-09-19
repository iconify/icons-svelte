<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrp9thb_f.css';
import '../../css/y/yewmc_bur.css';
import '../../css/h/hvsnt-1bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lrp9thb_f"/><path class="yewmc_bur"/><path class="hvsnt-1bk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:touch-2" {...props}></Icon>
