<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8ap1vbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8ap1vbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:user-new" {...props}></Icon>
