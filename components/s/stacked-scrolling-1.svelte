<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tygmpgx5r.css';
import '../../css/p/pin_d6b9x.css';
import '../../css/a/a5yv6_bwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="tygmpgx5r"/><path class="pin_d6b9x"/><path class="a5yv6_bwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:stacked-scrolling-1" {...props}></Icon>
