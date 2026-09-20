<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/elyed7l1j.css';
import '../../css/g/g2ejn3rhn.css';
import '../../css/a/aldj5jhrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="elyed7l1j"/><path class="g2ejn3rhn"/><path class="aldj5jhrk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:socket-outline" {...props}></Icon>
