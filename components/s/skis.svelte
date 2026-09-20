<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eri4cjb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eri4cjb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:skis" {...props}></Icon>
