<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h8sz2mb9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h8sz2mb9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:square-kanban-plus" {...props}></Icon>
