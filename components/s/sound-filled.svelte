<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qk1mjebnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qk1mjebnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:sound-filled" {...props}></Icon>
