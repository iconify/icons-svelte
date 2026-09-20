<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvfwd6dby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kvfwd6dby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms-5" {...props}></Icon>
