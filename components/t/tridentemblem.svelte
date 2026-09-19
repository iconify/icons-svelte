<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b9zq02yuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b9zq02yuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:tridentemblem" {...props}></Icon>
