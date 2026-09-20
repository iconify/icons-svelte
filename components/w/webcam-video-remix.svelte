<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j35i7-b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="j35i7-b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:webcam-video-remix" {...props}></Icon>
