<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmivc1y4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmivc1y4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:user-circle-info" {...props}></Icon>
