<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/occiy068q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="occiy068q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-dashed-kanban" {...props}></Icon>
