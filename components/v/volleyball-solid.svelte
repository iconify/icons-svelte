<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9v37qbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9v37qbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:volleyball-solid" {...props}></Icon>
