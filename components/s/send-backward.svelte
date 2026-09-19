<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cn3v3rbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cn3v3rbfz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:send-backward" {...props}></Icon>
