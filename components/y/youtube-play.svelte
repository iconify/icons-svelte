<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kq4iw6b1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="kq4iw6b1s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:youtube-play" {...props}></Icon>
