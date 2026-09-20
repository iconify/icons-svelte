<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrb26zbcm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrb26zbcm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:truck-electric" {...props}></Icon>
