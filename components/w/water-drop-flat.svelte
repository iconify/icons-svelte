<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/r-8685bkx.css';
import '../../css/i/ii9ov8xwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="r-8685bkx"/><path clip-rule="evenodd" class="ii9ov8xwu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:water-drop-flat" {...props}></Icon>
