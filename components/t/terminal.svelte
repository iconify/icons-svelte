<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzmcj_lwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="kzmcj_lwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:terminal" {...props}></Icon>
