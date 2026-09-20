<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djvsyh2cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="djvsyh2cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nimbus:truck" {...props}></Icon>
