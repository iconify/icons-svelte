<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nm6p1mtnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nm6p1mtnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-3-filled" {...props}></Icon>
