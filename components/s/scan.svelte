<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfbgv4bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vfbgv4bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:scan" {...props}></Icon>
