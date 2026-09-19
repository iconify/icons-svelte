<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xuch1achf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xuch1achf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:zoom-in" {...props}></Icon>
