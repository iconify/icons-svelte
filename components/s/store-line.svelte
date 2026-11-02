<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qo__o3b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qo__o3b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:store-line" {...props}></Icon>
