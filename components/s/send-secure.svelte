<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzb-kg7ff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzb-kg7ff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:send-secure" {...props}></Icon>
