<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk8j7_b_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="tk8j7_b_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:vector" {...props}></Icon>
