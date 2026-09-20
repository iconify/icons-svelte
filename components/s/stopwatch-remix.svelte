<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vye12zu8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vye12zu8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:stopwatch-remix" {...props}></Icon>
