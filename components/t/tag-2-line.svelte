<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba874dbxc.css';
import '../../css/r/r-_tixcty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba874dbxc"/><path class="r-_tixcty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tag-2-line" {...props}></Icon>
