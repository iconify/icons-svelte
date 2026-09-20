<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tl83o0buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tl83o0buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:spider-thread" {...props}></Icon>
