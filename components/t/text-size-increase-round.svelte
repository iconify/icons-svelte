<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx364u-2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx364u-2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-size-increase-round" {...props}></Icon>
