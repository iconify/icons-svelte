<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtai9hb3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rtai9hb3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:scissors-solid" {...props}></Icon>
