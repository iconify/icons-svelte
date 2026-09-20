<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q74ok7b2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q74ok7b2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:send-duotone-line" {...props}></Icon>
