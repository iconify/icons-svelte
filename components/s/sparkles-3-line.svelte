<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ue600zb1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ue600zb1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sparkles-3-line" {...props}></Icon>
