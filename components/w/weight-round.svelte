<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl1_hpqhg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl1_hpqhg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:weight-round" {...props}></Icon>
