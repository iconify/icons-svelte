<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hiz9-olbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hiz9-olbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:stumbleupon" {...props}></Icon>
