<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bo-eui7wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bo-eui7wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:settings-2-line" {...props}></Icon>
