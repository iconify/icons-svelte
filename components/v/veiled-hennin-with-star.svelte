<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lbsuls3hw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lbsuls3hw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:veiled-hennin-with-star" {...props}></Icon>
