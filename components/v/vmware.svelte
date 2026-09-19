<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh2f03bwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rh2f03bwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:vmware" {...props}></Icon>
