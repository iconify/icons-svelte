<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xotfw-l2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xotfw-l2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:slack" {...props}></Icon>
