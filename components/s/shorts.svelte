<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfnsh61-s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tfnsh61-s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:shorts" {...props}></Icon>
