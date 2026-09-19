<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wr7325j1p.css';
import '../../css/v/vix1e0hxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wr7325j1p"/><path class="vix1e0hxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:sina-weibo" {...props}></Icon>
