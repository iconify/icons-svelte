<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atebddbcx.css';
import '../../css/o/odo83i1su.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="atebddbcx"/><path class="odo83i1su"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-kiss-heart" {...props}></Icon>
