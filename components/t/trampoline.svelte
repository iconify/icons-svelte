<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/of3dkvhwn.css';
import '../../css/f/f5456gr9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="of3dkvhwn"/><path class="f5456gr9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:trampoline" {...props}></Icon>
