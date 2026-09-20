<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvb-mac4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvb-mac4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:ruler-pen4-filled" {...props}></Icon>
