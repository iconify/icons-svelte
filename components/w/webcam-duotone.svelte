<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/p2wr1lf8y.css';
import '../../css/n/n33v813cm.css';
import '../../css/u/uvm1-pvtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p2wr1lf8y"/><path class="n33v813cm"/><path clip-rule="evenodd" class="uvm1-pvtu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:webcam-duotone" {...props}></Icon>
