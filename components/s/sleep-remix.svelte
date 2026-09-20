<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqd7-fwmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lqd7-fwmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:sleep-remix" {...props}></Icon>
