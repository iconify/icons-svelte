<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t2b0vdbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t2b0vdbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-sidebar-right-round" {...props}></Icon>
