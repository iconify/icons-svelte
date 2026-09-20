<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqrl-diou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xqrl-diou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:time-two-outline" {...props}></Icon>
