<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9sf339bt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9sf339bt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:tree-deciduous-solid" {...props}></Icon>
