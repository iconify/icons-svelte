<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vdldj9b0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vdldj9b0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:volcano" {...props}></Icon>
