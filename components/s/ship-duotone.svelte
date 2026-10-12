<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n7w3l1b0r.css';
import '../../css/i/iotgnquzk.css';
import '../../css/p/p0v030bro.css';
import '../../css/o/o82blrbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n7w3l1b0r"/><path class="iotgnquzk"/><path class="p0v030bro"/><path class="o82blrbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:ship-duotone" {...props}></Icon>
