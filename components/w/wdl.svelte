<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rls1xqfjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":356,"height":512};
const content = `<path class="rls1xqfjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:wdl" {...props}></Icon>
