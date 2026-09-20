<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgoay3b5b.css';
import '../../css/r/r9cdxubdv.css';
import '../../css/s/sm4hol1wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgoay3b5b"/><path class="r9cdxubdv"/><path class="sm4hol1wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:taking-pictures-circle" {...props}></Icon>
