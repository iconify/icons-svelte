<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tstl_rxkr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tstl_rxkr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoke-detector-alert" {...props}></Icon>
