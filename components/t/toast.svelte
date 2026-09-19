<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxpyd0bte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxpyd0bte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:toast" {...props}></Icon>
