<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tws5w2b2v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tws5w2b2v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:square-dashed-kanban" {...props}></Icon>
