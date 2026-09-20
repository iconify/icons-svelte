<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mq1lalb-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq1lalb-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:wallet-minus3-filled" {...props}></Icon>
