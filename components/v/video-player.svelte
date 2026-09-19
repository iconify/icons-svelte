<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ytibtjceb.css';
import '../../css/z/zb00v0bqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ytibtjceb"/><path class="zb00v0bqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:video-player" {...props}></Icon>
