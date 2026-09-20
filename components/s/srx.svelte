<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqdy2-y3t.css';
import '../../css/f/fs7pu5ekr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dqdy2-y3t"/><path class="fs7pu5ekr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:srx" {...props}></Icon>
