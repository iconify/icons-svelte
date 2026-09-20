<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kazes7o0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kazes7o0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-sun" {...props}></Icon>
