<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxmp01xwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="yxmp01xwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:travel-hotel-towel-towel-spa-wet-water-hot" {...props}></Icon>
