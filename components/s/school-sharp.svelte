<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0m-rizhq.css';
import '../../css/z/z0wxf4bfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p0m-rizhq"/><path class="z0wxf4bfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:school-sharp" {...props}></Icon>
