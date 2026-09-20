<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq5bo2w_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mq5bo2w_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:tillywork-light" {...props}></Icon>
