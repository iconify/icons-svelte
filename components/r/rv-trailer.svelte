<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gnanw2lxl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gnanw2lxl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:rv-trailer" {...props}></Icon>
