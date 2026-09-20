<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r5qruj8rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r5qruj8rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-line-icons:screen-desktop" {...props}></Icon>
