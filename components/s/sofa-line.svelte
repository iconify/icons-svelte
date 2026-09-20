<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/osv-pcb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="osv-pcb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sofa-line" {...props}></Icon>
