<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ng_zzxpne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ng_zzxpne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:vending-flower" {...props}></Icon>
