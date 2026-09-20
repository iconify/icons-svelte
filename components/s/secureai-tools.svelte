<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qadmupuce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qadmupuce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:secureai-tools" {...props}></Icon>
