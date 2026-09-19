<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oegn2i95m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="oegn2i95m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:send" {...props}></Icon>
