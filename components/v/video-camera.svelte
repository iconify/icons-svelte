<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jverfxb2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jverfxb2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:video-camera" {...props}></Icon>
