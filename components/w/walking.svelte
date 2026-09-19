<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i4fkzxbug.css';
import '../../css/x/xge6mkzpc.css';
import '../../css/v/vb0k3bbvx.css';
import '../../css/q/qiyipmlbn.css';
import '../../css/a/a2kqpsbnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="i4fkzxbug"/><path class="xge6mkzpc"/><path clip-rule="evenodd" class="vb0k3bbvx"/><path class="qiyipmlbn"/><path class="a2kqpsbnd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:walking" {...props}></Icon>
