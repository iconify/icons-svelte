<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgt9wsb6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bgt9wsb6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:text-center" {...props}></Icon>
