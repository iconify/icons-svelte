<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/igr5ktb8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="igr5ktb8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:wrench-off-filled" {...props}></Icon>
