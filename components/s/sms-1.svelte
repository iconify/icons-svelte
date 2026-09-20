<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqprf-bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jqprf-bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-1" {...props}></Icon>
