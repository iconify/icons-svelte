<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/y479ucc5d.css';
import '../../css/e/ei6majb8s.css';
import '../../css/o/odh5eyb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="y479ucc5d"/><path class="ei6majb8s"/><path clip-rule="evenodd" class="odh5eyb1n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:upload-track2-filled" {...props}></Icon>
