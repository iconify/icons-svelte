<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu0if9b0f.css';
import '../../css/q/qb2gh7q5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hu0if9b0f"/><path class="qb2gh7q5f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:square-kanban-plus-filled" {...props}></Icon>
