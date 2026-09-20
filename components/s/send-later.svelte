<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0j3n1bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d0j3n1bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:send-later" {...props}></Icon>
