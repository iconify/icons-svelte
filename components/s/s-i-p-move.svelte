<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gq26b0qdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="gq26b0qdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:s-i-p-move" {...props}></Icon>
