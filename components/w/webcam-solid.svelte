<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzuc2fb_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="uzuc2fb_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:webcam-solid" {...props}></Icon>
