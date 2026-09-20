<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aaa1ls8_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="aaa1ls8_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump-color:webcam-video-flat" {...props}></Icon>
