<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p9rtbeb4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p9rtbeb4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:toggle-right-2-fill" {...props}></Icon>
