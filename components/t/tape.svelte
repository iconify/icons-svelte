<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiedn7oku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiedn7oku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:tape" {...props}></Icon>
