<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf1043y0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="jf1043y0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:school-jp-11" {...props}></Icon>
