<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pthc7kbbw.css';
import '../../css/i/ig-kolbmk.css';
import '../../css/p/plk3fn3le.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="pthc7kbbw"/><path class="ig-kolbmk"/><path class="plk3fn3le"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-duotone" {...props}></Icon>
