<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d20po3bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d20po3bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:square-kanban-plus" {...props}></Icon>
