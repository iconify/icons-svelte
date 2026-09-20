<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx001kbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qx001kbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:stack-overflow-line" {...props}></Icon>
