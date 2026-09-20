<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3w3uox9w.css';
import '../../css/j/j4n3fkkjr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="s3w3uox9w"/><path class="j4n3fkkjr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:websocket" {...props}></Icon>
