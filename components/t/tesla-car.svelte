<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixrhjab8n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixrhjab8n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:tesla-car" {...props}></Icon>
