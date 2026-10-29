<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxr_0bc2h.css';
import '../../css/y/yqpjzibdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxr_0bc2h wm-a"/><path class="wm-k yqpjzibdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:thumbs-up" {...props}></Icon>
