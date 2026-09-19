<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q36m0bb5w.css';
import '../../css/x/x84itwbxe.css';
import '../../css/o/otwfeac8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="q36m0bb5w"/><path class="x84itwbxe"/><path class="otwfeac8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="clarity:tape-drive-line" {...props}></Icon>
