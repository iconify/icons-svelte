<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9x77lmsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="b9x77lmsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:video-camera" {...props}></Icon>
