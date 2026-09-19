<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpg4mpn-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpg4mpn-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:server-cluster" {...props}></Icon>
