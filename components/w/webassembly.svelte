<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o8h7at49z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o8h7at49z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:webassembly" {...props}></Icon>
