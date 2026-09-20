<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srp64xlvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="srp64xlvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:text-align-left" {...props}></Icon>
