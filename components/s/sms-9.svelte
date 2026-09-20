<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_k0w1bio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s_k0w1bio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-9" {...props}></Icon>
