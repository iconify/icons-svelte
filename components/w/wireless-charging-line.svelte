<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6x7wfcnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6x7wfcnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:wireless-charging-line" {...props}></Icon>
