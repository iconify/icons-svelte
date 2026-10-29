<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/s/sbrvwfb0g.css';
import '../../css/q/q08n-4bjs.css';
import '../../css/b/btlgwpbsn.css';
import '../../css/z/z6q0xzsvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="sbrvwfb0g"/><path class="q08n-4bjs wm-a"/><path class="btlgwpbsn"/><path class="z6q0xzsvv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:sun-moon-duo" {...props}></Icon>
