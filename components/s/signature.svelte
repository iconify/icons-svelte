<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn5gx4_1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="yn5gx4_1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:signature" {...props}></Icon>
