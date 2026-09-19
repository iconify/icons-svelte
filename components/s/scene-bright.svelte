<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fh0ww_rwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh0ww_rwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:scene-bright" {...props}></Icon>
