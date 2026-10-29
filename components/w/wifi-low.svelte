<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6-o6yb-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p6-o6yb-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:wifi-low" {...props}></Icon>
