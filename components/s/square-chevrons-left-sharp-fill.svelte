<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf1crc8bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wf1crc8bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-chevrons-left-sharp-fill" {...props}></Icon>
