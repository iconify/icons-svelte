<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/og5k9ackk.css';
import '../../css/x/x2q17r7hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="og5k9ackk"/><path class="x2q17r7hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:simplex-chat" {...props}></Icon>
