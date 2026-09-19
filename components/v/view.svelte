<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz9gs3blk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz9gs3blk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:view" {...props}></Icon>
