<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rlma8nb5g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1080,"height":674};
const content = `<path clip-rule="evenodd" class="rlma8nb5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:webflow" {...props}></Icon>
