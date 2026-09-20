<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h_xbbgirr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h_xbbgirr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:voice-2-fill" {...props}></Icon>
