<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5f350l-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e5f350l-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:xmake" {...props}></Icon>
