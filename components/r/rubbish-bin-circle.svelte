<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xswv0rbkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xswv0rbkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:rubbish-bin-circle" {...props}></Icon>
