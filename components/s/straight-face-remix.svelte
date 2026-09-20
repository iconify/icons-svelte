<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfrrrab-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="rfrrrab-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:straight-face-remix" {...props}></Icon>
