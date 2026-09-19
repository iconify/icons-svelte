<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xduf9kbuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xduf9kbuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:user-settings" {...props}></Icon>
