<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjq3pxauu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjq3pxauu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-good" {...props}></Icon>
