<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysuq3zb1h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ysuq3zb1h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-3" {...props}></Icon>
