<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itqx26bnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="itqx26bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:transfer-vertical-line" {...props}></Icon>
