<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jsacoyt2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jsacoyt2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:sign" {...props}></Icon>
