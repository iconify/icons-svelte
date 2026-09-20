<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg5u6gbbk.css';
import '../../css/x/xfozdx-ki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xg5u6gbbk"/><path class="xfozdx-ki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:vending-medicine" {...props}></Icon>
