<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tkvs6705i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tkvs6705i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-2" {...props}></Icon>
