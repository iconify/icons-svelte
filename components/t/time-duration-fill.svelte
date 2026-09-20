<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/quzra8ibi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="quzra8ibi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:time-duration-fill" {...props}></Icon>
