<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/c/cms9251bd.css';
import '../../css/s/sf7yaz6nn.css';
import '../../css/o/okalx_bvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="cms9251bd"/><path class="sf7yaz6nn"/><path class="okalx_bvh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:user-round-arrow-left-duotone" {...props}></Icon>
