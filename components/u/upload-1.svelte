<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkikw8e4q.css';
import '../../css/x/xmqhqyf1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="xkikw8e4q"/><path class="xmqhqyf1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:upload-1" {...props}></Icon>
