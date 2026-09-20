<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2sx36b-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="k2sx36b-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:stopwatch-play-filled" {...props}></Icon>
