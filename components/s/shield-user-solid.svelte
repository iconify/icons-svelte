<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on85g6bhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on85g6bhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:shield-user-solid" {...props}></Icon>
