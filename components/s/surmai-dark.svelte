<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owv36ushu.css';
import '../../css/a/a0a2rfb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="owv36ushu"/><path class="a0a2rfb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:surmai-dark" {...props}></Icon>
