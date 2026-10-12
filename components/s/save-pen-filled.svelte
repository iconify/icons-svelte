<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a8cln5bam.css';
import '../../css/j/j0iubn3mf.css';
import '../../css/i/is0qnibip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a8cln5bam"/><path class="j0iubn3mf"/><path class="is0qnibip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-pen-filled" {...props}></Icon>
