<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixvd5vfvp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ixvd5vfvp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:subtitle-line" {...props}></Icon>
