<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x9vy97b6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x9vy97b6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:server" {...props}></Icon>
