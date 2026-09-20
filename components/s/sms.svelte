<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vkevy7b_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vkevy7b_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:sms" {...props}></Icon>
