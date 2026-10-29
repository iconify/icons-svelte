<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bol868bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bol868bvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:traffic-cone-solid" {...props}></Icon>
