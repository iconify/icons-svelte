<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei5tqekdn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":460,"height":512};
const content = `<path class="ei5tqekdn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:stdlibjs" {...props}></Icon>
