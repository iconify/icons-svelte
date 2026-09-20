<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bk44c3j1d.css';
import '../../css/s/sf98jwb3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bk44c3j1d"/><path class="sf98jwb3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:server-api-cloud" {...props}></Icon>
