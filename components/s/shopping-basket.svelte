<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv3nwjbqk.css';
import '../../css/d/da5fxxb_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="yv3nwjbqk"/><path class="da5fxxb_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:shopping-basket" {...props}></Icon>
