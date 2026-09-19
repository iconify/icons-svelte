<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gj0x1lb9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gj0x1lb9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:wrist-watch-filled" {...props}></Icon>
