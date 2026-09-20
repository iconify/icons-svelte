<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqod7_waq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iqod7_waq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-1-line" {...props}></Icon>
