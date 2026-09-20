<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwqvfkb2i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wwqvfkb2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:zhihu" {...props}></Icon>
