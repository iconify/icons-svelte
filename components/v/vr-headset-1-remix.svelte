<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yawj8c32a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yawj8c32a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vr-headset-1-remix" {...props}></Icon>
