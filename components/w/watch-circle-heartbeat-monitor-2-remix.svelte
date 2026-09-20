<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl16l82px.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="pl16l82px"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:watch-circle-heartbeat-monitor-2-remix" {...props}></Icon>
