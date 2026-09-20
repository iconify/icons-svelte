<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5eoflcbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="d5eoflcbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:spray" {...props}></Icon>
