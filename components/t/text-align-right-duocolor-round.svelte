<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvguh3b_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rvguh3b_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:text-align-right-duocolor-round" {...props}></Icon>
