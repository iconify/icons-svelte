<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9vj8vb-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1792};
const content = `<path class="c9vj8vb-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:x-square" {...props}></Icon>
