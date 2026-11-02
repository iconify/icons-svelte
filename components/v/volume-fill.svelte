<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6bef0f7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6bef0f7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:volume-fill" {...props}></Icon>
