<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zl-yckb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zl-yckb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:trend-down-outline" {...props}></Icon>
