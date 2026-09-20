<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nh8istksq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nh8istksq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:tool-box" {...props}></Icon>
