<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq8mqkgzd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq8mqkgzd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:star-solid" {...props}></Icon>
