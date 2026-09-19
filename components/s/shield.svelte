<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgtg1ybgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xgtg1ybgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:shield" {...props}></Icon>
