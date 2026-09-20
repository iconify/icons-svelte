<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s42bbq7uz.css';
import '../../css/d/do2_d_k7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s42bbq7uz"/><path class="do2_d_k7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:visible-by-verizon" {...props}></Icon>
