<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfec3yb0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfec3yb0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:surfboard-2" {...props}></Icon>
