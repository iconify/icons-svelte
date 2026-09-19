<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xb-1gwzgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xb-1gwzgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:spa" {...props}></Icon>
