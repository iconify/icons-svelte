<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kpsm7jb6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="kpsm7jb6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:webcam-video-solid" {...props}></Icon>
