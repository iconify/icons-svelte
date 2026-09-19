<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6dnwhibh.css';
import '../../css/q/qyrvrgbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n6dnwhibh"/><path class="qyrvrgbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:usb" {...props}></Icon>
