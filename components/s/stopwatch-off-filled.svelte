<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovr3h0b9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovr3h0b9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stopwatch-off-filled" {...props}></Icon>
