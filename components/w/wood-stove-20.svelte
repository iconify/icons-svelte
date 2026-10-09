<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2ylmobyz.css';
import '../../css/k/kzolceiuj.css';
import '../../css/c/ce_ntp43z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y2ylmobyz"/><path class="kzolceiuj"/><path class="ce_ntp43z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-stove-20" {...props}></Icon>
