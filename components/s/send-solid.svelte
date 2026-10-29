<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hx-_h68tb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hx-_h68tb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:send-solid" {...props}></Icon>
