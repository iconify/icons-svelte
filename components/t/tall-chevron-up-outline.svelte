<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lkbtpfb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lkbtpfb_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:tall-chevron-up-outline" {...props}></Icon>
