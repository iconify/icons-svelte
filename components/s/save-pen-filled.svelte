<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8cln5bam.css';
import '../../css/u/uu3z8f28g.css';
import '../../css/w/w42ds020q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8cln5bam"/><path class="uu3z8f28g"/><path class="w42ds020q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-pen-filled" {...props}></Icon>
