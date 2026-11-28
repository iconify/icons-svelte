<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srw_o6t-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="srw_o6t-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:safe" {...props}></Icon>
