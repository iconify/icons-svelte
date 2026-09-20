<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pb1aonl_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pb1aonl_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:sofa-line" {...props}></Icon>
