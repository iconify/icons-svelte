<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qn4zwfbgg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qn4zwfbgg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trending-down-line" {...props}></Icon>
