<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/onj001b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="onj001b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:videocam-sharp" {...props}></Icon>
