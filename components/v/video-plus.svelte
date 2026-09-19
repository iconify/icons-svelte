<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e0zmq8r3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e0zmq8r3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:video-plus" {...props}></Icon>
