<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l4xyy74qz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l4xyy74qz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:tag-plus" {...props}></Icon>
