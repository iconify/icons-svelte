<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4m5qijdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w4m5qijdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rustdesk-light" {...props}></Icon>
