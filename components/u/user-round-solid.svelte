<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b2182vpgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b2182vpgd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:user-round-solid" {...props}></Icon>
