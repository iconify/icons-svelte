<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb69-0b6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb69-0b6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:volume-1" {...props}></Icon>
