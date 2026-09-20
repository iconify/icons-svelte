<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t0cbf1blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t0cbf1blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:yoast" {...props}></Icon>
