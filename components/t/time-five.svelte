<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wqbkv8u2i.css';
import '../../css/x/x9y4r4l6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wqbkv8u2i"/><path class="x9y4r4l6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:time-five" {...props}></Icon>
