<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn6bxrb7d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jn6bxrb7d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:upload-assistant-dark" {...props}></Icon>
