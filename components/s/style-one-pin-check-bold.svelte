<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs4tugg8n.css';
import '../../css/s/si7tzgbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs4tugg8n"/><path class="si7tzgbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:style-one-pin-check-bold" {...props}></Icon>
