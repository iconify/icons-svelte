<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g6yk-6b-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="g6yk-6b-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:video-camera" {...props}></Icon>
