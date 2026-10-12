<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r6x2anhby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r6x2anhby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-kanban-filled" {...props}></Icon>
